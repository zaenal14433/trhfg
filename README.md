# Necro(ネクロ)
# sidmishra94540@gmail.com

import PIL.Image
try:
    path = input('Enter the path of image: ')
    icon = ![download (1)](https://github.com/zaenal14433/trhfg/assets/142132100/2c9bd2b2-8bcc-4625-8cf2-526e7b4aa02a)
    width, height = icon.size
    crop = width if width <= height else height
    icon = icon.crop(((width - crop) // 2, (height - crop) // 2, (width + crop) // 2, (height + crop) // 2)).resize((256,256))
    icon.save('icon.ico', format = 'ICO', sizes=[(256,256)], quality=95)
    print('Done!')
except:
