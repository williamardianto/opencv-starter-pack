# OpenCV functions Cheatsheet

### Common functions
1. Insert Text
<br>`cv2.putText(frame, "Hello OpenCV", (300,400), fontFace=cv2.FONT_HERSHEY_SIMPLEX, fontScale=1.0, color=(255, 0, 0),
            thickness=3)`
            
2. Resize Image
<br>`output = cv2.resize(frame, (600,400))`

3. Overlay image on image
<br>`output = cv2.addWeighted(src1=foreground, alpha=0.3, src2=background, beta=0.7, gamma=0)`

4. Make portrait mode using external webcam
<br>`rotated = cv2.rotate(frame, cv2.ROTATE_90_COUNTERCLOCKWISE)`

5. Save image to a file
<br>`cv2.imwrite('my_picture.jpg', frame)`