<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r761c-bxw"/><path class="m3bn7sb5q"/><path class="y-4o8e34g"/><path class="l7ynjsgwx"/><path class="wc595gblk"/><path class="aff9hemvj"/><path class="u36itk5tb"/><path class="m_erznomk"/><path class="tr__z6b9j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:endangered-duotone-thin" {...props}></Icon>
<style>
:global(.aff9hemvj) {
  d: path("M9 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l7ynjsgwx) {
  fill: currentColor;
  d: path("M18 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.m_erznomk) {
  d: path("M19 6v8");
}

:global(.m3bn7sb5q) {
  fill: currentColor;
  d: path("M9 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r761c-bxw) {
  fill: currentColor;
  d: path("M4 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tr__z6b9j) {
  d: path("M18 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.u36itk5tb) {
  d: path("M3 16a5 5 0 0 1 10 0 4 4 0 0 1 -5 4 4 4 0 0 1 -5 -4");
}

:global(.wc595gblk) {
  d: path("M4 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.y-4o8e34g) {
  fill: currentColor;
  d: path("M3 16a5 5 0 0 1 10 0 4 4 0 0 1 -5 4 4 4 0 0 1 -5 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
