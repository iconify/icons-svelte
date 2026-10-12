<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q7re2yxre"/><path class="iizkudbem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:humidifier" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iizkudbem) {
  d: path("M8.5 15.25c1.25-.75 2.25-.75 3.5 0s2.25.75 3.5 0m-6-7.75c-.75-.75.75-1.25 0-2s.75-1.25 0-2m5 4c-.75-.75.75-1.25 0-2s.75-1.25 0-2");
}

:global(.q7re2yxre) {
  width: 12.5px;
  height: 11.5px;
  x: 5.75px;
  y: 9.75px;
  rx: 3px;
}

</style>
