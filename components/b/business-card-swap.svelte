<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vdzw6_7kz"/><path class="f-56kqphr"/><path class="qykzcgbau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:business-card-swap" {...props}></Icon>
<style>
:global(.f-56kqphr) {
  d: path("m17 9.75l2 2l2-2M8.75 18H7.5A2.5 2.5 0 0 1 5 15.5v-3.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qykzcgbau) {
  d: path("m3 14.25l2-2l2 2");
}

:global(.vdzw6_7kz) {
  d: path("M5.125 2.5h4.75A2.625 2.625 0 0 1 12.5 5.125v1.75A2.625 2.625 0 0 1 9.875 9.5h-4.75A2.625 2.625 0 0 1 2.5 6.875v-1.75A2.625 2.625 0 0 1 5.125 2.5m9 12h4.75a2.625 2.625 0 0 1 2.625 2.625v1.75a2.625 2.625 0 0 1-2.625 2.625h-4.75a2.625 2.625 0 0 1-2.625-2.625v-1.75a2.625 2.625 0 0 1 2.625-2.625M15 6h1.5A2.5 2.5 0 0 1 19 8.5v3.25");
}

</style>
