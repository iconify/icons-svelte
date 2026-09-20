<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fxyvsab-e"/><path class="npenpvb6u"/><path class="ap7tcjbly"/><path class="vxi-y-5ue"/><path class="dpd39d9rw"/><path class="k44ucwlod"/><path class="tgth1rbuy"/><path class="wxng3f21w"/><path class="jdxsdlola"/><path class="awxqv1b4c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:carbon-footprint-duotone-thin" {...props}></Icon>
<style>
:global(.ap7tcjbly) {
  fill: currentColor;
  d: path("M10 3.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.awxqv1b4c) {
  d: path("M17 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.dpd39d9rw) {
  fill: currentColor;
  d: path("M17 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fxyvsab-e) {
  fill: currentColor;
  d: path("M7 11a5 5 0 0 1 10 0v6a5 5 0 0 1 -10 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jdxsdlola) {
  d: path("M14 3.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.k44ucwlod) {
  d: path("M7 11a5 5 0 0 1 10 0v6a5 5 0 0 1 -10 0Z");
}

:global(.npenpvb6u) {
  fill: currentColor;
  d: path("M6 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tgth1rbuy) {
  d: path("M6 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.vxi-y-5ue) {
  fill: currentColor;
  d: path("M14 3.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wxng3f21w) {
  d: path("M10 3.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
