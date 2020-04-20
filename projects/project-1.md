---
layout: project
type: project
image: images/micromouse.jpg
title: Set-up Connection a Linux Machine Behind a Home Router using SSH Tunnels by Vietnamese.
permalink: projects/ssh-tunnels
# All dates must be YYYY-MM-DD format!
date: 2020-04-20
labels:
  - Linux
  - Tunnels
  - SSH
summary: How to Access a Linux Machine Behind a Home Router With SSH Tunnels
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

AS a Data Scientist (DS), I'm always hungry for computation power. I have quite a powerful desktop at home; however, it's quite challanging to access the computer from anywhere because of dynamic IP. After spending a few hours for searching around, I found out a good way to tackle this problems. If English is not a problem to you, have a look [this link](https://juliansimioni.com/blog/howto-access-a-linux-machine-behind-a-home-router-with-ssh-tunnels/). This tutorial is for Vietnamese DS, it will be explained by Vietnamese. Tutorial này được chia sẽ bởi 1 top team kaggle từng có hạng 22 trên thế giới, trong đó có vài DS là người Việt (tất nhiên là không phải mình).

Một điều nửa là bài này không dành cho các bạn giàu, giàu thì thuê server của Azure với AWS đi cho lẹ :D, còn GCP thì ahihi.


Here is some code that illustrates how we read values from the line sensors:

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



