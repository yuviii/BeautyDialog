BeautyDialog Library
=================

The BeautyDialog library helps easy way to handle the dialog. It is very handy library to use and also the developer can edit it according to their neccesity.


###The library is in beta and under active development, expect bugs. <br>

![Screenshot](http://www.yubrajpoudel.com.np/Beautyphoto/Screenshot_2014-10-22-22-42-02.png)


Adding BeautyDialog to your project
================
###Eclipse
1) Download the ZIP file <br>
2) Extract the BeautyDialog project from the ZIP file <br>
3) In Eclipse: New > Android Project from Existing Code > Library > Finish <br>
4) Right click on your project <br>
5) Android > Library: Add > Library <br>



Using the library
================
1) create the linear layout where you want to display the beauty dialog	
	<p>
  LinearLayout
        android:id="@+id/dialog_container"
	 android:layout_width="match_parent"
	android:layout_height="wrap_content"
	android:background="#000000"
        android:orientation="horizontal"
	android:gravity="centre"
	android:padding="10dp"
	android:visibility="gone" </p>
2) write down the following code where you want trigger the Beauty Dialog

	Animatebox ab = new Animatebox(MainActivity.this);
	ab.setTextmesg("No Internet connection");
	ab.setAnimation(Utils.LENGTH_LONG);
	ab.setColor(Utils.BLUE);
	ab.setImage(R.drawable.ic_launcher);

	or
	Animatebox.Create(this, "No Internet Connection",R.drawable.ic_launcher, Utils.LENGTH_LONG);		}



Screenshot Of SAMPLES
================
A simple screenshot below shows the basic usability of the library. A sample provided with this library gives the comprehensive ideas about 
how to use the library effectively.
 A [Screenshot1](http://www.yubrajpoudel.com.np/Beautyphoto/Screenshot_2014-10-22-22-42-02.png)
 [Screenshot1](http://www.yubrajpoudel.com.np/Beautyphoto/Screenshot_2014-10-22-22-42-14.png)
[Screenshot1](http://www.yubrajpoudel.com.np/Beautyphoto/Screenshot_2014-10-22-22-42-19.png)
 Developer
=========
[Yubaraj Poudel](https://www.facebook.com/yubaraj.poudel.1)


License
=======

    Copyright 2014 Yubaraj Poudel

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
