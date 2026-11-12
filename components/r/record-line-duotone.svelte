<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVG6WNJNcPe)" class="caog0qvka"><circle class="doy9q4b5f"/><path class="h2th7gbpb"/></g><defs><clipPath id="SVG6WNJNcPe"><rect class="fng6irbns"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:record-line-duotone" {...props}></Icon>
<style>
:global(.caog0qvka) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.doy9q4b5f) {
  cx: 12px;
  cy: 12px;
  r: 10px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.fng6irbns) {
  width: 24px;
  height: 24px;
  fill: var(--svg-color--fff, #fff);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.h2th7gbpb) {
  d: path("M19.0711 4.92898C15.1658 1.02373 8.83418 1.02373 4.92893 4.92898C1.02369 8.83422 1.02369 15.1659 4.92893 19.0711");
}

</style>
