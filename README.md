# BEATS FROM BEYOND // Interactive Synthesizer

A zero-dependency, browser-based synthwave workstation powered by the native **Web Audio API**. Built as a single self-contained HTML file with real-time audio synthesis, a 16-step drum and bass sequencer, playable synth pads, and a live frequency visualizer.

---

## Features

* **100% Synthesized Audio:** Generates kicks, white-noise snares, crisp hi-hats, a pulsing sawtooth bassline, and lead synth tones directly in the browser without external audio samples or libraries.
* **16-Step Sequencer:** Interactive 4-track grid (`Kick`, `Snare`, `Hi-Hat`, `Bass`) that can be edited in real time while playing.
* **Playable Lead Synth Pads:** 8-key pad section tuned to a C Minor pentatonic synthwave scale (`C4` to `G5`). Supports both mouse clicks and keyboard shortcuts (`A` through `K`).
* **Real-Time Sound Shaping:**
  * **BPM Slider:** Adjust tempo smoothly from `70` to `170` BPM.
  * **Waveform Selector:** Switch lead oscillators between `Sawtooth` (80s Lead), `Square` (Retro Chip), and `Triangle` (Smooth).
  * **Master Low-Pass Filter:** Sweep cutoff frequencies from `200 Hz` to `6000 Hz`.
* **Live Frequency Visualizer:** HTML5 Canvas spectrum analyzer rendered in real time using `AnalyserNode`.

---

## Getting Started

Because **Beats From Beyond** has no external dependencies or build steps, running it takes seconds:

1. Save the HTML code as `index.html`.
2. Double-click `index.html` to open it in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Click **Play** to start the audio context and trigger the sequencer.

---

## Controls & Shortcuts

| Control / Key | Function |
| :--- | :--- |
| **Play / Stop** | Starts or stops the 16-step sequencer loop. |
| **Clear** | Resets all active steps across every sequencer track. |
| **BPM Slider** | Sets the playback speed (`70` – `170` BPM). |
| **Lead Wave** | Changes the oscillator waveform for the playable lead pads. |
| **Filter Slider** | Controls the master low-pass filter cutoff frequency. |
| **Keys `A` – `K`** | Triggers the 8 lead synth notes (`C4`, `Eb4`, `F4`, `G4`, `Bb4`, `C5`, `Eb5`, `G5`). |

---

## Tech Stack

* **HTML5 & CSS3:** Responsive CSS Grid layout, custom properties, and neon glassmorphism styling.
* **Vanilla JavaScript (ES6+):** Sequencer timing loop, DOM state management, and keyboard event listeners.
* **Web Audio API:** `AudioContext`, `OscillatorNode`, `AudioBufferSourceNode`, `BiquadFilterNode`, `GainNode`, and `AnalyserNode`.
* **HTML5 Canvas API:** Real-time 2D frequency bar rendering.

---

## License

Free to use, modify, and distribute for personal or educational projects.
