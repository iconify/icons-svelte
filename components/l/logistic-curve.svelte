<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j_q_y1bdx"/><path class="a0mcg5b_z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:logistic-curve" {...props}></Icon>
<style>
:global(.a0mcg5b_z) {
  d: path("M6.5 18.5c6.5 0 4.5-13 12.5-13");
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

</style>
