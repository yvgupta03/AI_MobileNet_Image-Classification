# AI_MobileNet_Image-Classification
AI based image classification inspired MobileNet V2 architecture by implementing changes in base architecture and details about using it as a quick response model (proposition) for rapid application as well as comparing it with other models for the same application.

More details in the ppt presenation file.

My approach roots from the technology that I have seen many times on my campus at the University of Texas at Dallas. There used be a food delivery vehicle automated to perceive its surrounding environment and act upon it to immediately avoid collision or navigate its route for food delivery in real time between actual crowd of human beings (including road traffic and zebra-crossing) based on real-time sensor data.

The dataset is actually quite poor and honestly a bit irrelevant to my goal of studying vehicle response. However, given the limited resources, I could only depend on Google's GPU which has limitations. Thus, I could not inculcate traffic signal dataset that has much more potential to produce better results for my study.

I thought about models based on low-inference time and quick response models using this as an inspiration. MobileNet V2 is a good architecture with limited amout of parameters which has been modified (on the level of its layers) during my approach to understand the applicability of this architecture. I have also looked into other image classification models before choosing mobilenet v2 as elaborated in ppt presentation. The Depthwise-pointwise convolution adapted in the model is the key to simplification. My goal is not to achieve higher accuracy through modifications on base model architecture, but rather its more about getting a decisive result for short inference time windows. There is also some hyper-parameter tuning involved to study how things change when we change different attributes of a working model.

There is also a python notebook based on transfer learning to understand the base scenrario of being able to resuse a subsidary model based on its learning from a similar dataset to understand how things are similar or different for that matter. This is just focused on observing similarity and so please ignore the poor performance by transfer learning model. 

### Note
There different folders within Python notebook folder for approaches taken to understand light image classfiction models. The MobileNet folder has different notebooks based on hyper-parameters tuned like '01' ending notebooks show learning rate of 0.01 and those without it are of 0.1
