---
layout: post
title: "First Post"
date: 2018-11-11
excerpt: "Examples and code for displaying images in posts."
tags: [first post, sample post, images, test]
comments: true
---

We first meet at 2018-06-02.

### One Up


<figure>
	<a href="https://github.com/zhuangtongzxy/zhuangtongzxy.github.io/blob/master/images/f1823d7ab9eab98f0ca682ae4.jpeg"><img src="https://github.com/zhuangtongzxy/zhuangtongzxy.github.io/blob/master/images/f1823d7ab9eab98f0ca682ae4.jpeg"></a>
	
</figure>



#### Two Up

If you want to display two or three images next to each other responsively use `figure` with the appropriate `class`. Each instance of `figure` is auto-numbered and displayed in the caption.

Apply the `half` class like so to display two images side by side that share the same caption.

{% highlight html %}
<figure class="half">
    <a href="/images/image-filename-1-large.jpg"><img src="/images/image-filename-1.jpg"></a>
    <a href="/images/image-filename-2-large.jpg"><img src="/images/image-filename-2.jpg"></a>
    <figcaption>Caption describing these two images.</figcaption>
</figure>
{% endhighlight %}



