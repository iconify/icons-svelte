<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eb-erwbma"/><path class="wdl9m7bcs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:camp-wagon" {...props}></Icon>
<style>
:global(.eb-erwbma) {
  d: path("M5.625 6h7.75A2.625 2.625 0 0 1 16 8.625v3.75A2.625 2.625 0 0 1 13.375 15h-7.75A2.625 2.625 0 0 1 3 12.375v-3.75A2.625 2.625 0 0 1 5.625 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wdl9m7bcs) {
  d: path("M3 17.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m8 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M16 9l4.5-4.5m-1.25-1.25l2.5 2.5");
}

</style>
