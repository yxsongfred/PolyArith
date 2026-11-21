# Utilities for model architecture
## \_\_init\_\_.py
Assembled functions provided for calling outside the directory
## activation.py
Declaration of activation functions excluded in PyTorch (SiLU)
## attention.py
Multi-head attention scheme with K-V cache, expanding across absolute position embedding (standard Transformer), relative position embedding (Transformer-XL, DeBERTa) and rotary position embedding (RoPE)
## embedding.py
Word embedding and different types of position embeddings
## inference.py
Main function for model training, validation and testing
## norm.py
Normalization scheme excluded in PyTorch (RMS Norm)
## polynormer.py
Obsolete attempt for Polynormer
## transformer.py
Main file defining Transformer models