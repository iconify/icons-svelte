<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="w5c3o5b4m"/><path class="ns7_8y4gv"/><rect class="i7dvbqwsv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bid-paddle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i7dvbqwsv) {
  width: 2.5px;
  height: 5.5px;
  x: 10.75px;
  y: 15.75px;
  rx: 1.25px;
}

:global(.ns7_8y4gv) {
  d: path("M10.75 7.25L12.25 6v5.5");
}

:global(.w5c3o5b4m) {
  cx: 12px;
  cy: 8.75px;
  r: 6px;
}

</style>
