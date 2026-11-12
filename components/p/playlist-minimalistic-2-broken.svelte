<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ltwq23bbr"/><path class="z4exszsav"/><path class="fbnn_3bad"/><circle class="gvyc-o7fz"/><path class="rgnmckb3y"/><path class="bv2ncrb-z"/><path class="u9kct68nj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:playlist-minimalistic-2-broken" {...props}></Icon>
<style>
:global(.bv2ncrb-z) {
  d: path("M3 6H10.4118M13.4118 6H15");
}

:global(.fbnn_3bad) {
  d: path("M17 16.5V12.5V8");
}

:global(.gvyc-o7fz) {
  cx: 14.5px;
  cy: 16.5px;
  r: 2.5px;
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ltwq23bbr) {
  d: path("M9 14H3");
}

:global(.rgnmckb3y) {
  d: path("M21 12C18.7909 12 17 10.2091 17 8");
}

:global(.u9kct68nj) {
  d: path("M13 10L6.82353 10M4.32353 10H3");
}

:global(.z4exszsav) {
  d: path("M8 18H3");
}

</style>
