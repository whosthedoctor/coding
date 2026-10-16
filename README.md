# coding

A C++ development environment demo: a preconfigured Codespace (Docker container
+ VS Code) for building C/C++ with CMake and Conan — zero local setup.

## What's inside

- `src/` — sample C application (`zenofgithub.c`, built with CMake + Conan)
- `.devcontainer/` — the container definition: compiler, CMake, Conan, and
  editor config, all preinstalled

## Usage

Open in GitHub Codespaces, then in a terminal:

```
cd build && make && cd bin && ./zenofgithub
```

Edit the code, rebuild, rerun — no environment wrestling required.
