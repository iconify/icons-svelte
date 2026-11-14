<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jne563b1p"/><path class="wffwimfhs"/><path class="blkwcq35c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hospital-administrator" {...props}></Icon>
<style>
:global(.blkwcq35c) {
  d: path("M15.5 14.5v7m5-7v7m-5-3.5h5");
}

:global(.jne563b1p) {
  d: path("M12.672 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.789 0 1.543.078 2.249.225M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wffwimfhs) {
  fill: currentColor;
  d: path("M10 14h1l.75 3.25L10.5 19l-1.25-1.75Z");
}

</style>
