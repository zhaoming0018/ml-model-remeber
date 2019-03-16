# Reasons
This repo copies from csong27/ml-model-remember. Due to python2.7 not supporting GPU well, I change the code to python3 implement, and remove the dataset in the repo to speed up downloading.

### Train a malicious model
python train.py --attack ATTACK 

Available ATTACK are cap (capacity abuse attack), cor (correlate value encoding attack) and sgn (sign encoding attack).

### Test attack quality 
python test_model --attack ATTACK
