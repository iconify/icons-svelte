<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="x-484gbyl"/><path class="wgasd9bfr"/><circle class="hcjpwwblz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:insulation-roll" {...props}></Icon>
<style>
:global(.hcjpwwblz) {
  cx: 9px;
  cy: 11px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wgasd9bfr) {
  d: path("M14.25 17h7");
}

:global(.x-484gbyl) {
  cx: 9px;
  cy: 11px;
  r: 6px;
}

</style>
