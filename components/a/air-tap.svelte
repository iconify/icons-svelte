<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="guyplobse"/><path class="omqe-motk"/><path class="zdli8kbcg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:air-tap" {...props}></Icon>
<style>
:global(.guyplobse) {
  d: path("M10 21.5v-11a2 2 0 0 1 4 0v4h3a2 2 0 0 1 2 2v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.omqe-motk) {
  d: path("M7 11.5a5 5 0 1 1 10 0");
}

:global(.zdli8kbcg) {
  d: path("M4.25 12a8 8 0 1 1 15.5 0");
}

</style>
