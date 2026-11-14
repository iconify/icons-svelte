<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="k0zqeccla"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:expand-square" {...props}></Icon>
<style>
:global(.g6ulkabjn) {
  d: path("M2.5 2.5h19v19h-19Z");
}

:global(.k0zqeccla) {
  d: path("m14 10l3.5-3.5m-3 0h3v3M10 10L6.5 6.5m3 0h-3v3M10 14l-3.5 3.5m0-3v3h3M14 14l3.5 3.5m0-3v3h-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
