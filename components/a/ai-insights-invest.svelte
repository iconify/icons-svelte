<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j_q_y1bdx"/><path class="w5wzm_bad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ai-insights-invest" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j_q_y1bdx) {
  d: path("M3.5 3.5v17h17");
}

:global(.w5wzm_bad) {
  d: path("m7 16.5l3.5-4l2.5 2l3.5-4M17 3c.2 2.1 1 2.9 3 3c-2 .1-2.8.9-3 3c-.2-2.1-1-2.9-3-3c2-.1 2.8-.9 3-3");
}

</style>
