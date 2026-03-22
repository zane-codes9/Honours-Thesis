# CLAMSer: High-Throughput Analysis of Metabolic Data from the CLAMS Oxymax Machine

<img width="634" height="935" alt="image" src="https://github.com/user-attachments/assets/e0d11826-ac24-4de6-bc19-a7bbafbf9da7" />

[![Status](https://img.shields.io/badge/Status-Beta-orange.svg)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.33+-ff4b4b.svg)](https://streamlit.io)

Metabolic data analysis is laborious and time-consuming. CLAMSer is an open-source, completely free tool for metabolic data processing. Specifically tailored for Columbus Instruments CLAMS systems, common in molecular biology labs. 

Done in completion of honours thesis for my BSc. 

**[➡️ Application](https://clamser.streamlit.app/)**

**[▶️ Video Walkthrough](https://www.youtube.com/watch?v=LuBnGmRzcB8)**

---

*   Upload all your raw `.csv` files at once (batch processing)
*   Analyze entire dataset or use presets for the last 24/48/72 hours, or custom window.
*   Define experimental groups
*   Switch results view between **Absolute**, **Body Weight Normalized**, and **Lean Mass Normalized** values.
*   Visualize timeline charts (color-coded by group) and summary bar charts.
*   Download summary CSV files ready for statistical software (SPSS, Jamovi, GraphPad Prism).

---

## Feedback & Beta Status

CLAMSer is currently in public beta. We are seeking feedback from researchers.

If you have a moment, please provide feedback on the questions:

* Does the `Upload -> Setup -> Process -> Export` workflow make sense for how you typically work? Are there any steps that feel confusing/out of place?
* Does the application address the most critical, time-consuming parts of your initial data processing? Are there any omissions in the core feature set (e.g., a specific normalization method, a key summary statistic)?
* The goal of CLAMSer is to be a "bridge" to statistical software. Does the exported CSV provide the data in a format that would be immediately useful for you in Prism, R, SPSS, or other?

Please send any thoughts, bug reports, or suggestions to Zane Khartabill (me) at `mkhal061@uottawa.ca` or [open an issue](https://github.com/zane-codes9/CLAMSer/issues) on this GitHub repository. Thanks!
