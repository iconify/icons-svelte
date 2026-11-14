<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j_q_y1bdx"/><path class="dzo-7_b_w"/><path class="tis6peu_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:all-time-low" {...props}></Icon>
<style>
:global(.dzo-7_b_w) {
  d: path("M7.5 6.5L11 12l3-2.5l3.5 7");
}

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

:global(.tis6peu_x) {
  fill: currentColor;
  d: path("M16 16.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
