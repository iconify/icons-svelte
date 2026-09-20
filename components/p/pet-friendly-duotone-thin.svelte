<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rvz2lnbll"/><path class="m3bn7sb5q"/><path class="uk8jjybxx"/><path class="nxfhmrd0m"/><path class="keqc2pbxm"/><path class="aff9hemvj"/><path class="r8g367bdl"/><path class="dx0ubwbyy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pet-friendly-duotone-thin" {...props}></Icon>
<style>
:global(.aff9hemvj) {
  d: path("M9 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dx0ubwbyy) {
  d: path("M7 16a5 5 0 0 1 10 0 4 4 0 0 1 -5 4 4 4 0 0 1 -5 -4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.keqc2pbxm) {
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.m3bn7sb5q) {
  fill: currentColor;
  d: path("M9 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nxfhmrd0m) {
  fill: currentColor;
  d: path("M7 16a5 5 0 0 1 10 0 4 4 0 0 1 -5 4 4 4 0 0 1 -5 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r8g367bdl) {
  d: path("M14.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.rvz2lnbll) {
  fill: currentColor;
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uk8jjybxx) {
  fill: currentColor;
  d: path("M14.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
