# Tasks Parser

## Overview

**Tasks Parser** is a Windows scheduled tasks forensics tool that detects anomalies, validates signatures, identifies disguised executables, and uncovers hidden registry-only tasks indicating potential malicious activity.

## Features

- **Signature Verification** - Detects unsigned, fake, or stolen certificates
- **Proxy Execution Detection** - Identifies renamed system executables used for evasion
- **Heuristic Analysis** - Flags suspicious task configurations and command-line arguments
- **Registry Mismatch Detection** - Discovers registry-only tasks without XML files (GhostTask persistence)
- **Advanced Filtering** - Sort and filter by logon triggers, signatures, and detection types
- **Quick Copy** - **Shift + Click** any cell to copy its contents

## Usage

1. Run as **Administrator** (required)
2. Wait for automatic scanning
3. Use filters to review flagged tasks
4. Investigate suspicious detections

## Detection Capabilities

### Signature Analysis
- Stolen/fake certificate detection

### Renamed Executables
Detects disguised system tools (e.g., cmd.exe renamed as chrome.exe)

### Registry Anomalies
Identifies tasks hidden in registry but missing XML definitions

## Credits

**Author:** zedoon @ Red Lotus Forensics / MarsMC SS Team

**Special Thanks:**
- 2020 @ Red Lotus Forensics
- Spok @ Red Lotus Forensics

## Disclaimer

For legitimate security research and forensics only. Users are responsible for compliance with applicable laws.
