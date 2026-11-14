<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="teru8hosf"/><path class="u4mi32bzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pharmacy-queue" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.teru8hosf) {
  d: path("M7.5 2.5h9a2 2 0 0 1 2 2V14a2 2 0 0 0 0 4v1.5a2 2 0 0 1-2 2h-9a2 2 0 0 1-2-2V18a2 2 0 0 0 0-4V4.5a2 2 0 0 1 2-2");
}

:global(.u4mi32bzh) {
  d: path("m10 7.25l2.5-1.75v7M10.25 16h3.5");
}

</style>
