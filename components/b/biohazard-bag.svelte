<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mgpldu_ny"/><path class="esldzgbqf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:biohazard-bag" {...props}></Icon>
<style>
:global(.esldzgbqf) {
  d: path("M14 9.5a2.5 2.5 0 1 1-4 0a2 2 0 0 0 4 0m1.5 9.5a2.5 2.5 0 1 1 2-3.25a2 2 0 0 0-2 3.25m-9-3.25a2.5 2.5 0 1 1 2 3.25a2 2 0 0 0-2-3.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mgpldu_ny) {
  d: path("M8.5 7c-3 2.5-4 6-3.5 9.5c.5 3.25 3.25 5 7 5s6.5-1.75 7-5c.5-3.5-.5-7-3.5-9.5Zm1 0l-1-4.5l3.5 2l3.5-2l-1 4.5");
}

</style>
