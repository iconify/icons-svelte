<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c045-yb6a"/><path class="mlb7ycbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lightbulb-led" {...props}></Icon>
<style>
:global(.c045-yb6a) {
  d: path("M9 15c0-1.5-3-3-3-6.5a6 6 0 0 1 12 0c0 3.5-3 5-3 6.5Zm0 0v2.5h6V15m-4.5 2.5V21m3-3.5V21");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mlb7ycbzh) {
  d: path("m9.5 11l1.25-2.5L12 11l1.25-2.5L14.5 11");
}

</style>
