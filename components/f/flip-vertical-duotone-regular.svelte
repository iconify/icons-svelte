<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="px3d6ogdu"/><path class="ubwz847cc"/><path class="fnp0mpbza"/><path class="qdo8thqpt"/><path class="xucfzr8ng"/><path class="y0y0ccsoe"/><path class="zy54a7bml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flip-vertical-duotone-regular" {...props}></Icon>
<style>
:global(.fnp0mpbza) {
  d: path("m5 9 7 -7 7 7Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.px3d6ogdu) {
  fill: currentColor;
  d: path("m5 9 7 -7 7 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qdo8thqpt) {
  d: path("m5 15 7 7 7 -7Z");
}

:global(.ubwz847cc) {
  fill: currentColor;
  d: path("m5 15 7 7 7 -7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xucfzr8ng) {
  d: path("M3 12h4");
}

:global(.y0y0ccsoe) {
  d: path("M10 12h4");
}

:global(.zy54a7bml) {
  d: path("M17 12h4");
}

</style>
