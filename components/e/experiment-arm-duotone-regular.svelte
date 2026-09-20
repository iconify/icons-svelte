<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jzeve79sx"/><path class="t_3t7fbzp"/><path class="mjolzzblm"/><path class="ymw3aibdo"/><path class="rz466126m"/><path class="ew7bcuc4w"/><path class="on0qv5szw"/><path class="qmhkuacxl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:experiment-arm-duotone-regular" {...props}></Icon>
<style>
:global(.ew7bcuc4w) {
  d: path("M13.5 6.5 18 11");
}

:global(.jzeve79sx) {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mjolzzblm) {
  fill: currentColor;
  d: path("M17 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.on0qv5szw) {
  d: path("M2 14a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.qmhkuacxl) {
  d: path("M17 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.rz466126m) {
  d: path("M10.5 6.5 6 11");
}

:global(.t_3t7fbzp) {
  fill: currentColor;
  d: path("M2 14a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ymw3aibdo) {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
