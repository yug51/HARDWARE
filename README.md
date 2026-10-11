# DIY Handheld Game Console

## Overview
A custom-designed, open-source DIY handheld retro gaming console powered by a Single Board Computer and custom hardware controls. Designed following a modular, layer-by-layer philosophy for easy assembly and upgradeability.

## Features
* **Retro Emulation:** Runs RetroPie to emulate classic gaming systems (NES, SNES, PS1, Game Boy, etc.).
* **Custom Controls:** Integrated physical D-pad, ABXY buttons, shoulder triggers, and analog thumbsticks managed via a microcontroller.
* **Portable Power:** Built-in UPS and battery system for true on-the-go gaming.
* **Compact Display:** Features an integrated IPS screen with built-in audio.

## Repository Structure
* `/firmware` - Microcontroller source code (e.g., Arduino `.ino` files) for the gamepad interface.
* `/pcb` - Schematic and board layout files (`.kicad_pcb`, `.kicad_sch`, etc.).
* `/cad` - 3D-printable case files (STL / STEP).

## Bill of Materials (BOM)
* Raspberry Pi (Model 4 / 3 / Zero 2W)
* Arduino Micro / Pro Micro
* 5-inch 800x480 IPS Screen
* PiSugar UPS & Battery Module
* Tactile push buttons and analog joystick modules

## Getting Started
1. **Firmware:** Flash the code located in the `/firmware` directory to your microcontroller.
2. **PCB / Hardware:** Use the schematic and layout files in `/pcb` for manufacturing or wiring reference.
3. **Assembly:** 3D print the enclosure files and assemble the hardware layer by layer following standard electronics safety practices.

