# My-Store

My-Store is an AltStore-compatible source repository for the Fan Controller app.

## Overview

This repository contains the app package and the metadata required for AltStore to discover and install the app.

- App name: Fan Controller
- Bundle identifier: `gizmogrid.Fan-Controller`
- Developer: Gizmogrid
- Description: Control your Atomberg fans from one app.
- Subtitle: Control your Atomberg fans

## Repository contents

- `apps.json` — AltStore source definition with app metadata, version history, and download links
- `Fan Controller.ipa` — packaged iOS app binary for installation
- `README.md` — project documentation

## App details

The metadata in `apps.json` defines the following source information:

- Source name: Gizmogrid AltStore Source
- Source identifier: `com.gizmogrid.source`
- Icon URL: `https://wrtdwh.github.io/My-Store/icon.png`

## Version history

### v1.1
- Release date: 2026-11-10
- Build: `1.02`
- Notes: "New Features and Bug fixes."
- Size: 189079 bytes
- Download: `https://github.com/wrtdwh/My-Store/releases/download/v1.1/Fan.Controller.ipa`

### v1.0
- Release date: 2026-11-09
- Build: `1`
- Notes: "Initial release."
- Size: 180510 bytes
- Download: `https://github.com/wrtdwh/My-Store/releases/download/v1.0.0/Fan.Controller.ipa`

## Installation

To use this repository with AltStore, add the source URL generated from the hosted repo.

Example:

`https://wrtdwh.github.io/My-Store/apps.json`

Then open AltStore, add the source, and install Fan Controller.

## Notes

This repository acts as a lightweight AltStore source for distributing the Fan Controller app.
