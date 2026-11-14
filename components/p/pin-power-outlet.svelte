<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jsztq_emy"/><path class="j51f-ebgg"/><path class="lqryz6b3u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-power-outlet" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j51f-ebgg) {
  d: path("M6 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

:global(.jsztq_emy) {
  d: path("M9.5 2.5h5a7 7 0 0 1 7 7v5a7 7 0 0 1-7 7h-5a7 7 0 0 1-7-7v-5a7 7 0 0 1 7-7");
}

:global(.lqryz6b3u) {
  fill: currentColor;
  d: path("M8.5 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0m5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
