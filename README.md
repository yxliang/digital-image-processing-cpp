# digital-image-processing-cpp
cpp implementation for algorithms in the book "数字图像处理与机器视觉-Visual C++与Matlab实现"

## CH3 pixel operation

### Threshold
Set threshold as 100:

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/Threshold_100.png" alt="drawing" height="200"/>

### Linear Transform

Set `dFa` as `2.0`, set `dFb` as `-55`:

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/Linear_Transform_2.00_-55.00.png" alt="drawing" height="200"/>

### Gamma Transform

Set `gamma` as `1.8`, set `comp` as `0`:

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/Gamma_Transform_1.80_0.00.png" alt="drawing" height="200"/>

### Log Transform

Set `dC` as 10:

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/Log_Transform.png" alt="drawing" height="200"/>

### Partial Linear Transform

Set `x1`, `x2`, `y1`, `y2` as `20`, `50`, `100`, `200`:

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/Log_Paritial_Linear_Transform_20_50_100_200.png" alt="drawing" height="200"/>

### Histogram equalization

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/Histogram_Equalization_128.png" alt="drawing" height="200"/>

### Histogram matching to dark 

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/Histogram_Matching_to_Dark.png" alt="drawing" height="200"/>

### Histogram matching to light

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/Histogram_Matching_to_Light.png" alt="drawing" height="200"/>

## CH4 geometric transformation

### Move

Move `20` right and `50` down:

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/Move_20_50_rgb.png" alt="drawing" height="200"/>

### Horizontal mirror

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/Horizontal_Mirror_rgb.png" alt="drawing" height="200"/>

### Vertical mirror

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/Vertical_Mirror_rgb.png" alt="drawing" height="200"/>

### Scale

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/Scale_1.50_rgb.png" alt="drawing" height="200"/>

### Rotate

Rotate 30 degrees counterclockwise:

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/Rotate_30.00_rgb.png" alt="drawing" height="200"/>

### Image projection restore

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/Projection_Restore_1.png" alt="drawing" height="200"/>

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/Projection_Restore_2.png" alt="drawing" height="200"/>


## CH5 spatial domain image enhancement

### Smooth average

Kernel size 3:

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/SmoothAvg.png" alt="drawing" height="200"/>

Kernel size 5:

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/SmoothAvg5.png" alt="drawing" height="200"/>

Kernel size 7:

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/SmoothAvg7.png" alt="drawing" height="200"/>

### Smooth gaussian

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/SmoothGauss.png" alt="drawing" height="200"/>

### Log edge detection

<img src="https://github.com/keineahnung2345/digital-image-processing-cpp/blob/master/images/result/LogEdgeDetection.png" alt="drawing" height="200"/>
