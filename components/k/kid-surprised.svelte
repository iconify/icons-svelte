<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="guks-vhlg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:kid-surprised" {...props}></Icon>
<style>
:global(.guks-vhlg) {
  d: path("M7 10.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m7 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M7.25 7q1.25-1 2.5 0m4.5 0q1.25-1 2.5 0m-6.5 9.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oy9aotbsd) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

</style>
