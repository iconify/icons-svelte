<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><path class="a1ybhtpxk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-arrow-left-up-linear" {...props}></Icon>
<style>
:global(.a1ybhtpxk) {
  stroke-linejoin: round;
  d: path("M15 15L9 9M9 13.5V9H13.5");
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

</style>
