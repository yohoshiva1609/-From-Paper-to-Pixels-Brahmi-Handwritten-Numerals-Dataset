# -From-Paper-to-Pixels-Brahmi-Handwritten-Numerals-Dataset


This repository contains a handwritten dataset of **Brahmi script numerals (0–9)** created as part of a structured pipeline designed for low-resource scripts. The dataset includes **200 image samples per numeral**, collected, processed, and stored in class-specific folders.

---

## Dataset Summary

- **Script**: Brahmi (Ancient Indian numeral system)
- **Classes**: 10 (Digits 0 to 9)
- **Samples per Class**: 200
- **Format**: Grayscale images (.png), size 28×28
- **Data Type**: Image only (CSV files not included currently)
- **Use Case**: Machine Learning / Deep Learning for handwritten character recognition

---

## Methodology Overview

This dataset was created using a structured, step-by-step pipeline as described below:

1. **Data Collection**  
   Handwritten Brahmi numerals were collected from participants aged 15–60 using a printed template.

2. **Digitization**  
   Sheets were scanned using an **Infinix GT smartphone** camera (any high-res phone can be used).

3. **Segmentation**  
   Characters were segmented using Python and OpenCV with contour detection and basic OCR principles.

4. **Data Organization**  
   Each character image was saved into class-specific folders named `0`, `1`, ..., `9`.

5. **Preprocessing**  
   Images were converted to grayscale, binarized (black and white), and resized to 28×28 pixels.

6. **Augmentation**  
   Data augmentation was applied using `ImageDataGenerator` to increase the dataset size to 200 samples per class.


Note: Download the brahmi_handwritten dataset.zip file this file is whole data 

