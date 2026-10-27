# Elisabeth Yap

**Electrical & Computer Engineering, Rowan University — Class of 2027**
Embedded hardware · PCB design · power systems

I build hardware end to end: schematic, layout, firmware, bench bring-up, and the enclosure it ships in. Right now that means IoT sensing hardware for my startup, protection and reliability work on the distribution grid at Atlantic City Electric, and a growing interest in microelectronics and semiconductors.

[![Website](https://img.shields.io/badge/elisabethyap.dev-1f2937?style=flat-square&logo=googlechrome&logoColor=white)](https://elisabethyap.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/elisabeth-yap/)
[![Email](https://img.shields.io/badge/Email-elyp2049%40hotmail.com-6b7280?style=flat-square&logo=microsoftoutlook&logoColor=white)](mailto:elyp2049@hotmail.com)

---

## Featured work

### LaundryIQ — real-time laundry monitoring for shared facilities
*Co-founder & COO · NSF I-Corps funded*

- ESP32-S3 sensor node on a custom PCB, taken through **5 hardware revisions**
- Reworked the analog front-end to reach **±0.01 A** current-sensing resolution
- Firmware classifies machine state (idle / running / done) from current-draw patterns and streams it to a live cloud dashboard
- Field-serviceable, screw-closed IP20 enclosure designed in SolidWorks
- 20+ customer-discovery interviews through NSF I-Corps

→ [KiCad source for the V2 board](https://github.com/yappy20/yap_LIQ_PCB_V2)

### SnapBin — camera-based inventory for electronic components
Point a webcam, Raspberry Pi, or ESP32-CAM at a part and SnapBin identifies it, files it into a bin location, and tracks stock against project BOMs. FastAPI + React in a single Docker container, with Arduino and Python capture-station firmware.

→ [yappy20/snapBin](https://github.com/yappy20/snapBin)

### AI Note Recorder
Real-time voice-to-notes device built from scratch on an ESP32: designed the audio capture circuit, wrote the C++ firmware for I2S mic input, and wired speech recognition into an LLM summarization pipeline — **95% transcription accuracy, 100 ms end-to-end latency**.

### Smart Grid Monitoring & Protection Dashboard
Distribution-feeder simulation with recloser lockout logic, fuse behavior, fault injection, and frequency-droop response — built to mirror the protection work I do in the field.

### Hand-built digital logic
A 4-IC traffic light controller and a Tetris arcade control board, both hand-soldered and debugged with an oscilloscope and DMM, with SolidWorks-designed 3D-printed enclosures and BOMs under $20 and $43.

### Software projects
| Project | What it is | Stack |
|---|---|---|
| **Ka-in** | AI recipe app live on iOS & Android — photos, receipts, or leftovers → recipes | Flutter, Firebase, Gemini, GPT-4o Vision |
| [**Residency Match Calculator**](https://github.com/yappy20/residency_match) | Couples-match probability from real NRMP data, deployed on Vercel | React, Vite |
| [**GAMMO**](https://github.com/yappy20/GammoMin) | Iterated Prisoner's Dilemma tournament simulator | C++, CMake, Python |
| **Geometry Dash IRL** | Play the real game by physically jumping — webcam tracking fires the input | Python, OpenCV |

---

## Experience

**Atlantic City Electric (Exelon)** — Electrical Engineering Co-op · *Jun 2024 – present*
Recloser and fuse settings review, GIS-to-feeder-map validation (50+ maps, 13 discrepancies resolved), 30+ recloser maps, smart-grid device inspections, and CAIDI/SAIDI/SAIFI reliability analysis.

**Rowan University, College of Engineering** — AI Research Assistant · *Jan 2024 – Jan 2025*
Labeled 150+ aerial images and collaborated on a PyTorch model for aerial object classification.

**BioDome Inc.** — Research Intern · *Feb – May 2025*
Benchmarked LoRa, Zigbee, and Wi-Fi IoT platforms across 8 vendors; wrote 6 technical comparison reports.

**IEEE Rowan Student Chapter** — Vice Chair · *2024 – present*
Organized the 2026 IEEE Student Activities Conference (250+ attendees, $50K budget) and co-organized ProfHacks 2024–2026.

---

## Toolbox

**Hardware & EDA** — KiCad · Altium Designer · LTspice · SolidWorks · Quartus
**Bench** — Oscilloscope · logic analyzer · signal generator · bench supply · DMM · hand soldering
**Embedded** — ESP32 / ESP32-S3 · Arduino · embedded C++ · I2C · SPI · I2S
**HDL** — Verilog · VHDL
**Software** — Python · C++ · Java · JavaScript / TypeScript · React · Next.js · Flutter · Firebase · PyTorch · OpenCV
**Power systems** — three-phase analysis · protective device coordination · transmission line modeling · reliability indices
