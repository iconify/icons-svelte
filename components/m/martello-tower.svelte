<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oup90w9wv"/><path class="dp9hi1b5p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:martello-tower" {...props}></Icon>
<style>
:global(.dp9hi1b5p) {
  d: path("M10.5 16.5v-3a1.5 1.5 0 0 1 3 0v3M3 20.5q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

:global(.oup90w9wv) {
  d: path("M7 4.5h10l2 12H5Zm-.5 3h11");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
