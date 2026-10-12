<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="lf2baemcn"/><path class="w-tlhd72z"/><circle class="ygphxfbhc"/><path class="oezf-fi1u"/><circle class="t0uxwyknr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:blood-cells" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lf2baemcn) {
  cx: 8.25px;
  cy: 8.25px;
  r: 5.5px;
}

:global(.oezf-fi1u) {
  d: path("M16 17.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

:global(.t0uxwyknr) {
  cx: 18.75px;
  cy: 5.5px;
  r: 2.25px;
}

:global(.w-tlhd72z) {
  d: path("M6.25 8.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.ygphxfbhc) {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
}

</style>
