# PriorityQueue
This is an implementation of the Priority Queue in C#, for use with Unity.

Unity requires a custom implementation of the Priority Queue because the [.NET Priority Queue](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.priorityqueue-2?view=net-7.0) requires .NET 7.0. Unity currently only supports v4.x.

## Source Material

This implementation here is cloned from [Blue Raja](https://github.com/BlueRaja), specifically, [High-Speed-Priority-Queue-for-C-Sharp](https://github.com/BlueRaja/High-Speed-Priority-Queue-for-C-Sharp). 

It has been cloned to enable the Unity package manager (UPM) to access and update this extension. Other tools in other repositories will benefit from being able to declare UPM dependencies and auto-import the package.


## Unity Package Manager support /#upm

Add to your project via the Unity Package Manager. 
1. In the Package Manger, select "Add package from Git URL..."
2. Type in `https://github.com/yohash/PriorityQueue.git#upm`

The `upm` branch is maintained us a current subtree via:
```
git subtree split --prefix=Assets/PriorityQueue --branch upm
```
