<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jzeve79sx"/><path class="znztjab3f"/><path class="unova7b3b"/><path class="w3q1h2boi"/><path class="ezg__mbcy"/><path class="t1ic5ob8h"/><path class="ymw3aibdo"/><path class="n-059ea3n"/><path class="olmwgycdy"/><path class="lc4ougb3r"/><path class="if5ft31dv"/><path class="bie4u9bix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hnsw-duotone-regular" {...props}></Icon>
<style>
:global(.bie4u9bix) {
  d: path("M19 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ezg__mbcy) {
  fill: currentColor;
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.if5ft31dv) {
  d: path("M11 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.jzeve79sx) {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lc4ougb3r) {
  d: path("M3 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.n-059ea3n) {
  d: path("M5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.olmwgycdy) {
  d: path("M15 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.t1ic5ob8h) {
  fill: currentColor;
  d: path("M19 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.unova7b3b) {
  fill: currentColor;
  d: path("M15 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.w3q1h2boi) {
  fill: currentColor;
  d: path("M3 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ymw3aibdo) {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.znztjab3f) {
  fill: currentColor;
  d: path("M5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
