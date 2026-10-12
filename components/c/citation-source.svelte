<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fubr_7bdu"/><circle class="rl5edqb6f"/><path class="i_bm-y0di"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:citation-source" {...props}></Icon>
<style>
:global(.fubr_7bdu) {
  d: path("M5.25 4.75h5.82a6.5 6.5 0 0 0 4.68 8.32v5.68a2.5 2.5 0 0 1-2.5 2.5h-8a2.5 2.5 0 0 1-2.5-2.5V7.25a2.5 2.5 0 0 1 2.5-2.5m.75 5.5h4M6 14h6.5M6 17.75h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i_bm-y0di) {
  d: path("m16.5 5.6l1-.85v4");
}

:global(.rl5edqb6f) {
  cx: 17.25px;
  cy: 6.75px;
  r: 4px;
}

</style>
