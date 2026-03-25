# RobyCare – Soft Robotic System for Neonatal Tactile Stimulation

This repository contains the datasets and supplementary material associated with the study:

**“RobyCare: A Soft Robotic System for Neonatal Tactile Stimulation”**

The work presents a soft pneumatic robotic system designed to emulate clinically inspired tactile stimulation patterns for neonatal care, based on experimentally measured force data from a trained neonatology specialist.

---
## Repository Structure

- **RobyCare/**
  - **data/**
    - calibration/
    - clinician_force/
    - control_results/
  - **docs/**
    - AI_prompts.txt/
  - **figures/**
    - paper/
    - supplementary/
  - **video/**
    - Supplementary_Video_S1.mp4
  - README.md

    
## Data Description

### clinician_force/
This folder contains representative force measurements acquired from a trained neonatology specialist during tactile stimulation experiments. These data were used to define the therapeutic force ranges employed in the control design.

### control_results/
This folder includes representative datasets from the pneumatic control system experiments, including variables such as pressure, PWM signals, and actuator activation.

Due to the large number of experimental trials, only a subset of representative datasets is provided. These datasets capture the typical system behavior and are sufficient to support the results presented in the paper. Additional data can be provided upon reasonable request.

### calibration/
This folder contains calibration data for the current sensing system used in the safety monitoring of the pneumatic actuation.

---

## Figures

### figures/paper/
Contains the final figures included in the manuscript.

### figures/supplementary/
Contains additional figures supporting the experimental results.

---

## Supplementary Material

### Video S1

The file `Supplementary_Video_S1.mp4` presents:

- Tactile data acquisition using the measurement platform  
- Application of stimulation patterns by the specialist  
- Spacer calibration procedure
- Operation of the soft robotic system on a neonatal mannequin  

---

## Reproducibility

The datasets provided in this repository allow reproduction of the main processing steps described in the paper, including:

- Force signal analysis  
- Peak detection  
- Statistical characterization of tactile stimuli  
- Evaluation of control system behavior  

---

## Ethics Statement

No human subjects or patient data were involved in this study. Tactile inputs were obtained from a trained specialist using an instrumented platform for engineering characterization purposes. No personal or identifiable information is included.

---

## AI Usage Transparency

AI-based tools (ChatGPT, OpenAI) were used exclusively for language refinement and improvement of manuscript clarity. These tools supported grammar correction, readability enhancement, and alignment with academic writing standards.

No AI tools were used for generating data, experimental results, or scientific conclusions. All technical content was developed and validated by the authors.

### Representative Prompts

- "Improve the clarity and academic tone of this paragraph while preserving its original meaning."
- "Refine this section to align with journal-style scientific writing without modifying the technical content."
- "Rewrite this paragraph to improve readability and conciseness."

---

## Contact

**Yarilenka Geraldine Benites Mozo**  
Universidad de Ingeniería y Tecnología - UTEC

yarilenka.benites.m@utec.edu.pe
