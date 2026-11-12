<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><path class="a44mazz6d"/><path class="wcvy2luch"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-double-alt-arrow-down-linear" {...props}></Icon>
<style>
:global(.a44mazz6d) {
  stroke-linejoin: round;
  d: path("M9 8.5L12 11.5L15 8.5");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.shu3xdl9q) {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

:global(.wcvy2luch) {
  stroke-linejoin: round;
  d: path("M9 12.5L12 15.5L15 12.5");
}

</style>
