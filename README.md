<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/program_info/org.prismlauncher.PrismLauncher.logo-darkmode.svg">
  <source media="(prefers-color-scheme: light)" srcset="/program_info/org.prismlauncher.PrismLauncher.logo.svg">
  <img alt="Steev Launcher" src="/program_info/org.prismlauncher.PrismLauncher.logo.svg" width="40%">
</picture>
</p>

<p align="center">
  Steev Launcher is a custom launcher for Minecraft that allows you to easily manage multiple installations of Minecraft at once.<br />
  <br />This is a <b>fork</b> of the MultiMC Launcher and is <b>not</b> endorsed by it.
</p>

# Features

- Every feature in Prism Launcher (mods, multi-accounts, skins, capes, offline and online accounts, multiple instances, etc...)
- Rebranded to "Steev Launcher"
- Custom theme and icon pack from `` (you can find their profile [here]())

## Useful build commands

```sh
git submodule update --init --recursive   # make submodules match this commit
cmake --preset linux                       # configures into ./build
cmake --build --preset linux --config Debug
ctest --preset linux --build-config Debug  # optional: run the tests (same as CI)
cmake --install build --config Debug       # installs into ./install
```
