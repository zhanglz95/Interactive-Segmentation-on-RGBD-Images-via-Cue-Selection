# Interactive-Segmentation-on-RGBD-Images-via-Cue-Selection
This is an implementation of ```Interactive Segmentation on RGBD Images via Cue Selection```.

### Dependencies
```
Python3.x (Tested with 3.6)
opencv
PyQt5
scikit-learn
PyMaxflow
Dijkstar
```
To Install PyMaxflow, please see [here].(https://github.com/pmneila/PyMaxflow)

For Dijkstar, please see [here].(https://github.com/wylee/Dijkstar)

### Note
The implementation is based on my own understanding of the paper, there may be some differences from the paper.And the other differences are some modifications which I think the results are better.

In addition, I add a variate NORMAL to control whether to take normal cue into account, for sometimes it will get better results without normal cue. 
