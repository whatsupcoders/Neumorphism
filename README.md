# Neumorphism


Neumorphism (aka neomorphism) is a relatively new design trend and a term that's gotten a good amount of buzz lately.
<p>It derives its name from skeumorphism – a way of integrating real-world objects into user interface design.</p>
<br/>
Well inorder to understand Neumorphism we need understand what is <b>Skeuomorphism</b> and <b>flat designs</b> 
<br/>
<P> In the below series of image it gives you a evolution of design starting from Skeuomorphism and then the flat designs and finally the Neumorphism.</p>
<br/>
<p><img src ="assets/2_Skeumorphic design.jpg" width ="300px" height="450px" />    <img src ="assets/3_Flat design.jpg" width ="300px" height="450px" />    <img src ="assets/1_Neumorphic design.jpg" width ="300px" height="450px" /></p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>Skeuomorphism</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>Flat design</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>Neumorphism</b></p>
<h2>Skeuomorphism</h2>
<br/>
Skeuomorphism is a term used to define an interface that mimics real-world items. to cite you with an example it is like the 
recycle bin icon on the desktop screen and the dial icon on mobile phones. However these 3-dimensions looking elements started looking unnecessary and made the UI look cluttered and that's when the existence of Flat Design came into existence.
<br/>
<br/>
<p align="center"><img src ="assets/banner.jpg" width ="450px" /></p>
<h2>Flat Design</h2>
<p>Flat design is a user interface design style that uses simple, two-dimensional elements and bright colors and it makes it feel like all the objects are lying on a Single Surface.</p>
<br/>
<br/>
<p align="center"><img src ="assets/flatdesign.jpg" width ="450px" /></p>
<br/>
<br/>
<h2>Neumorphism</h2>
<br/>
<p>Neumorphic design draws from both skeumorphism and flat design by pairing a monochromatic color palette with subtle shadows, while giving a sense of 3-dimensions in the form of buttons and other elements.</p>
<p> what makes it unique is the game of shadows and shades that Neumorphism uses to create very realistic buttons and objects. It gives the users a distinct feel. </p>
<br/>
<br/>
<p align="center"><img src ="assets/theme1.png" width ="300px" height="450px" /></p>
<h2> Benefits of Neumorphism</h2>
<ul>
  <li>It adds 3D feel for real buttons and Visual Freshness.</li>
  <li>Overloaded interfaces are bypassed by users.</li>
  <li>Neumorphic designs remain a timeless classic.</li>
  <li>It accelerates the process of conceptualizing, building, testing, and iterating new screens.</li>
</ul>

<p> This is the library reference <a href = "https://github.com/applibgroup/Neumorphism">Here</a> </p>

<p>Let's see some of the components created with Neumorphic effect </p>

# Alert
Alert components use to notify user of information

Let's see how to create the alert component in HarmonyOS.

<h3> Step 1</h3>
Import: the node component and you can refer that from library <a href ="https://github.com/applibgroup/Neumorphism/blob/main/neumorphism/alert/alert.hml"> here </a> as shown below. 

```html
<element name='neualert' src='../../../../../../alert.hml'></element>
```
<h3> Step 2</h3>
<p> now we need use the tag named "neualert" and define the parameters like icon and Text as shown below.
  
Usage:
```html
<neualert icon="/heart.png" width="300px" height="60px" border="40px" >
  <text>Alert !</text>
</neualert>
```
That's it by doing this we will get the below Neumorphic alert design.

<img src="assets/alert.PNG" width="" height="">
<hr>

# Card
Now let'se how to implement a card design.

<h3> Step 1</h3>
Import: the node component and you can refer that from library <a href ="https://github.com/applibgroup/Neumorphism/blob/main/neumorphism/card/card.hml"> here </a> as shown below. 

Import:
```html
<element name='neucard' src='../../../../../../card.hml'></element>
```
<h3> Step 2</h3>
<p> Now we need use the tag named "neucard" and define the parameters like height, width and border as shown below and a image to display inside the card, you can replace it with text as well.
  
Usage:
```html
<neucard width="300px" height="200px" border="10px" >
  <image src="common/placeholder.png" ></image>
</neucard>
```
That's it by doing this we will get the below Neumorphic card design.

<img src="assets/card.PNG" width="" height="">
  <hr/>
Similarly we can implement the below list of components.

| Components   | Display                                            |Properties |
| -------------| -------------                                      |------------- |
| <b><a href ="https://github.com/applibgroup/Neumorphism/tree/main/entry/src/main/js/default/pages/node_modules/hmos-neumorphism/avatar">avatar</a></b>       | <img src="assets/card.PNG" width="" height=""/>  |icon, width,height,border
| <b><a href="https://github.com/applibgroup/Neumorphism/tree/main/entry/src/main/js/default/pages/node_modules/hmos-neumorphism/button">button </a> </b>     | <img src="assets/button.PNG" width="" height=""/>  |  icon, width,height,border, buttonevent
| <b><a href="https://github.com/applibgroup/Neumorphism/tree/main/entry/src/main/js/default/pages/node_modules/hmos-neumorphism/buttons">buttons </a></b>     | <img src="assets/buttons.PNG" width="" height=""/>  |width,height,border, slot
| <b><a href="https://github.com/applibgroup/Neumorphism/tree/main/entry/src/main/js/default/pages/node_modules/hmos-neumorphism/checkbox">checkbox </a> </b>    | <img src="assets/checkbox.PNG" width="" height=""/>  | checked,check-event,color 
| <b><a href="https://github.com/applibgroup/Neumorphism/tree/main/entry/src/main/js/default/pages/node_modules/hmos-neumorphism/dropdown">dropdown</a> </b>    | <img src="assets/dropdown.PNG" width="" height=""/>  |change-event
| <b><a href= "https://github.com/applibgroup/Neumorphism/tree/main/entry/src/main/js/default/pages/node_modules/hmos-neumorphism/form">form </a>   </b>     | <img src="assets/form.PNG" width="" height=""/>  |submit-event,reset-event
| <b><a href="https://github.com/applibgroup/Neumorphism/tree/main/entry/src/main/js/default/pages/node_modules/hmos-neumorphism/input">input</a>  </b>      | <img src="assets/input.PNG" width="" height=""/>  |icon , type, maxlength,placeholder 
| <b><a href="https://github.com/applibgroup/Neumorphism/tree/main/entry/src/main/js/default/pages/node_modules/hmos-neumorphism/label">label</a> </b>       | <img src="assets/label.PNG" width="" height=""/>  |text,icon
| <b><a href="https://github.com/applibgroup/Neumorphism/tree/main/entry/src/main/js/default/pages/node_modules/hmos-neumorphism/navbar">navbar</a>  </b>     | <img src="assets/navbar.PNG" width="" height=""/>  |left-event,middle-event,right-event
| <b><a href="https://github.com/applibgroup/Neumorphism/tree/main/entry/src/main/js/default/pages/node_modules/hmos-neumorphism/pagination">pagination</a> </b>  | <img src="assets/pagination.PNG" width="" height=""/>  |color,previous-event,next-event        
| <b><a href="https://github.com/applibgroup/Neumorphism/tree/main/entry/src/main/js/default/pages/node_modules/hmos-neumorphism/progress">progress </a> </b>   | <img src="assets/progress.PNG" width="" height=""/>  |progress,width,color
| <b><a href="https://github.com/applibgroup/Neumorphism/tree/main/entry/src/main/js/default/pages/node_modules/hmos-neumorphism/radio">radio  </a>  </b>    | <img src="assets/radio.PNG" width="" height=""/>  |checked,check-event                    
| <b><a href="https://github.com/applibgroup/Neumorphism/tree/main/entry/src/main/js/default/pages/node_modules/hmos-neumorphism/switcher">switcher</a></b>     | <img src="assets/switch.PNG" width="" height=""/>  |toggle-event

<hr />
<p> Lets go through some of the usescases and there implementation using Neumorphic library<p>
<h3>Smart Watch</h3>
<p></p>
<br/>
<br/>
<p float="left" ><img src ="assets/smartwatch.png" /></p>
<h3>Smart Home Dark Theme</h3>
<p></p>
<br/>
<br/>
<p float="left" >
<img src="assets/smarthome_matepad.png" width="500px" height="">
<img src="assets/smarthome_phone.png" width="200px" height="">
</p>
<h3>Smart Home Light Theme</h3>
<p></p>
<br/>
<br/>
<p float="left" >
<img src="assets/livingroom_matepad.png" width="500px" height="">
<img src="assets/livingroom_phone.png" width="200px" height="">
</p>
<p> You can find the component implementation on HarmonyOS <a href ="https://github.com/applibgroup/Neumorphism"> here.</a>
<p> If you haven't tried this unique style of designing then give it a try. With that being said, designers have been coming up with new design ideas that expand on the concept of Neumorphism every day. I am excited to see the intersting components that you can create.</p>
