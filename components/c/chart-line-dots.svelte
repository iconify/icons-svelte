<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j_q_y1bdx"/><path class="br3qlragl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-line-dots" {...props}></Icon>
<style>
:global(.br3qlragl) {
  d: path("M5.75 16a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m4-6.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m4.5 4.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m3.5-7.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-9.25 8l2-3.5m2.25-.25l2 2m2-.25l2-4.5");
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
