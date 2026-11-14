<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sbynuxbok"/><path class="pp1grubkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:falling-rocks-sign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pp1grubkg) {
  fill: currentColor;
  d: path("M11 11a1 1 0 1 0 2 0a1 1 0 1 0-2 0m1.75 4.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.sbynuxbok) {
  d: path("m14.291 7.101l5.026 8.993A2.625 2.625 0 0 1 17.026 20H6.974a2.625 2.625 0 0 1-2.291-3.906l5.026-8.993a2.625 2.625 0 0 1 4.582 0M6.25 13.25L12.5 20");
}

</style>
