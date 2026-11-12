<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oe_q4780g"/><circle class="c55ag9btm"/><path class="roh-o2f0v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-2-linear" {...props}></Icon>
<style>
:global(.c55ag9btm) {
  cx: 9px;
  cy: 18px;
  r: 4px;
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oe_q4780g) {
  d: path("M13 18V10V2");
}

:global(.roh-o2f0v) {
  d: path("M19 8C15.6863 8 13 5.31371 13 2");
}

</style>
