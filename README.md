# Event DP

#### (Case study Engineering Career Expo, Unilag)

This is a volunteer project to create social media awareness for the student run event. Attendees input their name and upload an image to generate a customize ECX event dp.

You can find an online demo at [ECX](https://ecx.website/dp).

![eventDp homepage](https://github.com/geektutor/dp/blob/master/screenshot.png)

# Tools Used

- jquery.min.js - for dom event and manipulation
- jquery.cropit.js - client side cropping of user uploaded image
- JS - for client side image processing and merging
- themify-icon - to display icons

# Folder structure and files

```
- src/
	css/
		style.css 			:css to customize the page, hint: code from scratch
	fonts/
		kenyan_coffee/		:folder contains font files
		themify-icon.css 	:font css
		themify-*			:others themify css file
	img/
		frame.jpg 			:image frame where user image will be place/merge
		noimage.png 		:a fallback default image
	js/
		jquery.cropit.js 	:simple jquery image cropping plugin
		jquery.min.js 		:jquery official library
		main.js 			:custom js where the magic happens
- uploads/
	2019/
		dp/					:folder contains all dp generated
		thumbnail/			:folder contains all crop image thumbnails
- .htacess					:custom server file for file dir access
- index.html 				:main html file where magic happens

```

# How to run locally

- Open your command prompt and clone the repository by running

`git clone https://github.com/geektutor/dp.git`

- Copy the folder to your **WAMP** www root or **XAMPP** htdots
- Then run in a browser

---