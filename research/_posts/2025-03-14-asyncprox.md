---
layout: publication
categories: publications

title: A note on asynchronous Projective Splitting in Julia
subtitle: 
author: Utkarsh Sharma, Kashish Goel, Aryan Dua, Sebastian Pokutta, and  Zev Woodstock
use_math: false
venue: Preprint
link-code: https://github.com/zevwoodstock/AsyncProx

link-text: Preprint
link-download: /media/publications/asyncprox.pdf

featured-image: /media/async-img.png

date: 2025-03-14

---
While it has been mathematically proven that Projective Splitting
(PS) algorithms can converge in parallel and distributed computing
settings, to-date, it appears there were no open-source
implementations of the full algorithm with asynchronous computing
capabilities. 
This note fills this gap by providing a Julia implementation of the
asynchronous PS algorithm of Eckstein and Combettes for solving
fully nonsmooth convex optimization problems. Our methodology
includes inter-operability with existing packages within the Julia
ecosystem, and we also document observations from running this
algorithm asynchronously on problems in image processing and
machine learning. 
