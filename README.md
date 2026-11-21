# Neon Cyberpunk Synth Lab

Single-file, zero-dependency browser synthesizer built with HTML, CSS, and the Web Audio API.

**Live demo:** [https://ylnyorulmaz.github.io/Neon-Cyberpunk-Syhth/](https://ylnyorulmaz.github.io/Neon-Cyberpunk-Syhth/)

## Play

1. Open the link above (or serve `index.html` locally).
2. Click **POWER CORE** to unlock audio.
3. Use the on-screen keyboard or **A–L** (white) / **W E T Y U** (black).
4. Optional: connect a MIDI controller (Web MIDI API).

## Features

Dual oscillators, resonant LPF, dual ADSR, BPM-synced LFO, delay/reverb/distortion, neon visualizer, Synth Hacker challenges, and four animated presets.

## Local run

```bash
python3 -m http.server 8080 --bind 127.0.0.1
# open http://127.0.0.1:8080
```