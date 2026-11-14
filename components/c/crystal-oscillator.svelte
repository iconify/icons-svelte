<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="thsafob9h"/><path class="m3azqxp8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crystal-oscillator" {...props}></Icon>
<style>
:global(.m3azqxp8d) {
  d: path("M10.5 8.5h3v7h-3Zm-4 0v7m11-7v7");
}

:global(.thsafob9h) {
  d: path("M8 6h8v12H8Zm-5 6h3.5m11 0H21");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
