## Simple Image Editor  
This is a small project for practicing some image processing operations, written in C++. 


### Usage
#### Change brightness: 
Chaning the brightness of an image is accomplished by component-wise interpoated with a blck iamge. __Factor__ 1.0 preserve the current image, 0.0 gives the black image.  
arguments: -brightness __factor__ <sourceImage.bmp> outputImage.bmp 

#### Change Contrast:
Contrast can be controlled by using a constant gray image. This gray image has the average image luminance of the original image. Interpolation reduces contrast and extrapolation boosts it.  
arguments: -contrast __factor__ <sourceImage.bmp> outputImage.bmp 