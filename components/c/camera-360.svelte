<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mxzl1tbmo"/><path class="bp7whr02z"/><path class="wy3lou_ac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:camera-360" {...props}></Icon>
<style>
:global(.bp7whr02z) {
  d: path("M5.5 9.5a6.5 2.25 0 1 0 13 0a6.5 2.25 0 1 0-13 0Zm-2.5 6q9 7.5 18 0");
}

:global(.mxzl1tbmo) {
  d: path("M5.5 9.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wy3lou_ac) {
  d: path("M18.5 15.5H21V18");
}

</style>
