# WaveListen
End-to-End ASR system in PyTorch with conv + BiGRU architecture, CTC loss, and custom decoding. Built without pre-trained APIs, featuring MFCC/spectrogram preprocessing, noise handling, GPU-accelerated training, and WER-based evaluation.

# 🎧 WaveListen

WaveListen is a Speech-to-Text (STT) project built from scratch using deep learning techniques.  
It is designed to convert audio into accurate text without relying on third-party APIs.  

---

## 🚀 Features
- Speech-to-Text transcription from audio files
- Built using deep learning (CTC Loss, RNN/Transformer architectures)
- Supports custom datasets
- Lightweight and extensible for research/production use

---

## 📂 Project Structure
WaveListen/
│-- data/ # Dataset will be stored here after download
│-- models/ # Saved models
│-- notebooks/ # Jupyter notebooks for experiments
│-- src/ # Source code for preprocessing, training, inference
│-- requirements.txt # Dependencies
│-- README.md # Project documentation


---

## 📊 Dataset

This project uses the [LJ Speech Dataset](https://www.kaggle.com/datasets/mathurinache/the-lj-speech-dataset).


