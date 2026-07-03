# T-Embed Momentum Flasher

Web-based flasher for LilyGo T-Embed (ESP32-S3) running Momentum firmware.

## Usage

1. Open the [flasher page](https://zackmsa777-a11y.github.io/t-embed-momentum-flasher/) in Chrome or Edge
2. Connect your T-Embed via USB
3. Click "Select device" and pick your T-Embed
4. Click "Flash now" and wait for the progress bar to complete
5. Your T-Embed reboots automatically

## Firmware

Built from [m0lomalteser/Flipper-Zero-ESP32-Port](https://github.com/m0lomalteser/Flipper-Zero-ESP32-Port) (Momentum fork)
- Commit: 9597c9e
- Target: LilyGo T-Embed CC1101 (ESP32-S3)

## Flash offsets

| File | Offset |
|------|--------|
| bootloader.bin | 0x0 |
| partition-table.bin | 0x8000 |
| ota_data_initial.bin | 0xf000 |
| furi_esp32.bin | 0x20000 |
