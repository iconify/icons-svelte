<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="xtnw8yhak"/><path class="z65860edw"/><circle class="mxz2w86rj"/><circle class="wy0v_abdz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:karaoke-mic" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mxz2w86rj) {
  cx: 4.25px;
  cy: 9.5px;
  r: 1.25px;
}

:global(.wy0v_abdz) {
  cx: 7.75px;
  cy: 8.75px;
  r: 1.25px;
}

:global(.xtnw8yhak) {
  cx: 15.5px;
  cy: 8.5px;
  r: 4px;
}

:global(.z65860edw) {
  d: path("m12.12 6.88l5 5m-3.24-6.76l5 5m-7.07-.08l-8.45 8.82l1.78 1.78l8.78-8.47M5.5 9.5V3.75l3.5-1v6");
}

</style>
