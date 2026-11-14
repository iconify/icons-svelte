<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rdrodebxk"/><path class="jov7ywodi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:memory-profile" {...props}></Icon>
<style>
:global(.jov7ywodi) {
  d: path("M5.5 13.25L9 9.5l3.5 1.5l6-4.25");
}

:global(.rdrodebxk) {
  d: path("M2.5 4h19v12h-19ZM6 16v3.5m4-3.5v3.5m4-3.5v3.5m4-3.5v3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
