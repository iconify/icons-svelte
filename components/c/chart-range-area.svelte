<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u8nu1rpws"/><path class="v_ui7pbkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-range-area" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u8nu1rpws) {
  fill: currentColor;
  d: path("M2.5 8.5c4-4.5 7-.5 10.5-3c3-2 5.5-2.5 8.5-1.5v5.5c-3-.5-5.5 2-8.5 4c-3.5 2.5-6.5-1-10.5 2Z");
}

:global(.v_ui7pbkk) {
  d: path("M2.5 21h19");
}

</style>
