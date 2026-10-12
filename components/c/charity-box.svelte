<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="e9-7-8-2z"/><rect class="x0mnz6b2h"/><path class="nk7dinbrj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:charity-box" {...props}></Icon>
<style>
:global(.e9-7-8-2z) {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nk7dinbrj) {
  d: path("M9 12h6m-3 7.25L9.6 16.9a1.55 1.55 0 0 1 2.4-1.95a1.55 1.55 0 0 1 2.4 1.95Z");
}

:global(.x0mnz6b2h) {
  width: 16.5px;
  height: 11.75px;
  x: 3.75px;
  y: 9.5px;
  rx: 1.5px;
}

</style>
