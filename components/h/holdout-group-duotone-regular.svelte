<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j93aodlin"/><path class="f3oxrjbrz"/><path class="v7yx62j9c"/><path class="pbykkpb5u"/><path class="l2x-_sd5q"/><path class="xcjkf-bzr"/><path class="id5fryblw"/><path class="wa8tqsbro"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:holdout-group-duotone-regular" {...props}></Icon>
<style>
:global(.f3oxrjbrz) {
  fill: currentColor;
  d: path("M9 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.id5fryblw) {
  d: path("M15.5 4v16");
}

:global(.j93aodlin) {
  fill: currentColor;
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.l2x-_sd5q) {
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pbykkpb5u) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15.5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v7yx62j9c) {
  fill: currentColor;
  d: path("M17.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wa8tqsbro) {
  d: path("M17.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.xcjkf-bzr) {
  d: path("M9 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
