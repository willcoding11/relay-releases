# Relay — Releases

Public installer downloads and auto-update feed for the [Relay](https://relayserverhosting.com) desktop app.

Releases are produced automatically from the private source repository. Each tag publishes:

- `Relay-Setup-X.Y.Z.exe` (Windows)
- `Relay-X.Y.Z-arm64.dmg` (macOS, Apple Silicon)
- `Relay-X.Y.Z.AppImage` (Linux)
- `latest.yml` / `latest-mac.yml` / `latest-linux.yml` (electron-updater metadata)

Installed clients check this repo for updates automatically.
