[![Unity Build and APK Upload](https://github.com/yatima1460/Unity-2DPlatformerMicrogame-PipelineExample/actions/workflows/main.yml/badge.svg)](https://github.com/yatima1460/Unity-2DPlatformerMicrogame-PipelineExample/actions/workflows/main.yml)

Version used: Unity 2020.3.38f1

There isn’t much documentation needed, and that’s the beauty of a clean, lean and nice GitHub Actions pipeline.
In terms of improving the build process some form of cache can be added so the same exact codebase hash will not be built twice.

Other forms of improvement can be using GitHub Actions as a shim and calling a Python script that does the same so the build system becomes agnostic even to GitHub Actions and in case can be moved somewhere else like CircleCI, Azure, Travis etc…

But really... this is as simple as it gets!

I hope you will enjoy the simplicity of this :)
