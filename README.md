🛠 Technical Specs
## Firmware (C++ / ESP-IDF)
Concurrency: Leverages FreeRTOS tasks to handle MIDI message processing and BLE advertising independently, ensuring zero-latency performance.

Peripheral Management: Implements an efficient 4x4 matrix scanning algorithm with software-based debouncing logic.

Communication: Uses BLE (Bluetooth Low Energy) MIDI 1.0 protocol for seamless wireless integration with DAWs (Ableton, Logic Pro) and Web Browsers.

## Hardware (PCB Design)
Microcontroller: ESP32-WROOM-32 (Dual-core 240MHz).

Design Tool: EasyEDA for professional-grade PCB layout and routing.

Power Management: Integrated 3.3V LDO regulator and decoupling capacitors for signal integrity.

## Web Dashboard (JavaScript)
Web MIDI API: Direct hardware-to-browser communication without external drivers.

UI/UX: Responsive dashboard built with vanilla JavaScript (or React) to map MIDI notes and monitor device status in real-time.
