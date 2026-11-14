<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dw94rpbtz"/><path class="iy0p96bgf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bangle" {...props}></Icon>
<style>
:global(.dw94rpbtz) {
  d: path("M21 10a9.5 7 0 1 0 0 4");
}

:global(.iy0p96bgf) {
  d: path("M16.5 10a5.5 3.5 0 1 0 0 4m0-4H21m-4.5 4H21");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
