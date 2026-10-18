# Lazy as downloads

Installers for [Lazy as](https://lazyas.com), the point-and-talk review app. Press a shortcut, point at anything on
your screen and talk: you get numbered screenshot notes and a compact prompt for your AI.

The easiest way to get it is [lazyas.com/download](https://lazyas.com/download), which picks the right file and walks
you through the install. This repo only hosts the files; the app's source code isn't here.

| System | File |
|---|---|
| macOS 14 or later, Apple Silicon and Intel | `LazyAs.zip` |
| Windows 10 and 11, 64-bit | `LazyAs-Setup.exe` (no admin rights needed) or `LazyAs-Windows-portable.zip` |
| Linux x64 with an X11 desktop | `LazyAs-Linux-x64.tar.xz` |

Get them from the [latest release](https://github.com/yousefoghouneim-collab/lazyas-releases/releases/latest).
On a Mac or Linux you can also install or update from Terminal:

```sh
curl -fsSL https://lazyas.com/install.sh | sh
```

These early-access builds aren't notarized by Apple or code-signed for Windows yet, so opening a downloaded file
shows a security dialog the first time. [The install guide](https://lazyas.com/download) shows how to get past it.
Each release lists SHA-256 checksums in `SHA256SUMS.txt`.

Free during early access. [Licence agreement](https://lazyas.com/eula) · [Privacy](https://lazyas.com/privacy) ·
Support: support@lazyas.com

© 2026 The Crew MENA Art Production L.L.C.
