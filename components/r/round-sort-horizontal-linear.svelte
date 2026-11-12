<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><path class="c_dm05blc"/><path class="aq5i5kwsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-sort-horizontal-linear" {...props}></Icon>
<style>
:global(.aq5i5kwsa) {
  stroke-linejoin: round;
  d: path("M8 14.5L16 14.5M13.25 17L16 14.5L13.25 12");
}

:global(.c_dm05blc) {
  stroke-linejoin: round;
  d: path("M16 9.5L8 9.5M10.75 12L8 9.5L10.75 7");
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
