<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="doy9q4b5f"/><path class="tbl4j-bom"/><path class="gnrb8ib6h"/><path class="mvx2c_b9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:confounded-circle-line-duotone" {...props}></Icon>
<style>
:global(.doy9q4b5f) {
  cx: 12px;
  cy: 12px;
  r: 10px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.gnrb8ib6h) {
  stroke-linejoin: round;
  d: path("M16 12L14 10.5L16 9");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mvx2c_b9q) {
  stroke-linejoin: round;
  d: path("M15 16L14 15L13 16L12 15L11 16L10 15L9 16");
}

:global(.tbl4j-bom) {
  stroke-linejoin: round;
  d: path("M8 12L10 10.5L8 9");
}

</style>
