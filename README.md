# PhotExcel
PhotExcel is a tool that can be used to convert photos into a excel file (means you can view the photo in a excel file)

#  Example
  Input image:
  
  ![alt text](https://raw.githubusercontent.com/yagav/PhotExcel/main/flag.jpg)
  
  Output:
  
  ![alt text](https://raw.githubusercontent.com/yagav/PhotExcel/main/example.jpg)
  
  (!Note in some cells of the excel file there maybe some data so what you can do is press ```Ctrl+A``` and the delete it, so all the data in the cells will be deleted where the background of the cells will be untouched.)

# Code Example
  This is really simple to use, you just have to import it and then pass in the image path you want to convert, and then you will have to specify the size you want the output in, and you can also specify the path in where to save the file, and also you can mention the status as True or False where in by True the program will say in what task it is currently working on.
  
  ``` 
  import PhotExcel
  
  PhotExcel(Image_Path='path of image', size = (300,300), Save_Path='output.xlsx', Status=False)
  ```
  !Important: This version of PhotExcel only supports images of RGB color type. Maybe in the upcoming verion you will get the freedom to input other types of images.   

