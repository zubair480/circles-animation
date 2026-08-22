# Circles Animation

A 3D circle loader built with nothing but HTML and CSS. No JavaScript, no
libraries, two files.

## How it works

Fifteen nested circles sit inside a container tilted into 3D with
`perspective(500px) rotateX(60deg)`. Each circle animates on `translateZ`
between -100px and 100px, and every one gets an `animation-delay` staggered 0.1s
from its neighbour. That offset is the whole trick: the stack ripples like a
tunnel instead of pulsing as a single block.

## Run it

Open `index.html` in a browser. There is no build step.

## Files

`index.html` holds the container and the 15 spans. `style.css` holds the
perspective transform, the keyframes and the per-circle delays.
