# Initial EglantinePS5 build

This branch requests a full release build through the repository's existing pull_request GitHub Actions workflow.

No emulator source files, SDKs or compiler options are changed. The expected output is the `EglantinePS5` release ZIP containing `PPSA98515`.

## Build retry

A follow-up commit triggers the `pull_request` synchronization event for the PS5 release build. The emulator source and build configuration are unchanged.
