<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="xdhqn2b4q"/><circle class="k-bx946ur"/><path class="j8lzq0dce"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bike-commute" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j8lzq0dce) {
  d: path("M6 16.25L9 10h7m2 6.25l-2.75-9h2.25M9 10l3.5 6.25H6M9 10l.5-2.75m-1.25 0h2.5m6.75-.5c.25-2.25 1.25-3.25 3.5-3.5c-.25 2.25-1.25 3.25-3.5 3.5");
}

:global(.k-bx946ur) {
  cx: 18px;
  cy: 16.25px;
  r: 3.25px;
}

:global(.xdhqn2b4q) {
  cx: 6px;
  cy: 16.25px;
  r: 3.25px;
}

</style>
