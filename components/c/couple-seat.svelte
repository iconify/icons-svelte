<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dk0hjh2db"/><path class="ymfg-abwj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:couple-seat" {...props}></Icon>
<style>
:global(.dk0hjh2db) {
  d: path("M2.5 10a1.5 1.5 0 0 1 3 0v4h5v-4a1.5 1.5 0 0 1 3 0v4h5v-4a1.5 1.5 0 0 1 3 0v8h-19Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ymfg-abwj) {
  d: path("M5.5 10V5.5A1.5 1.5 0 0 1 7 4h2a1.5 1.5 0 0 1 1.5 1.5V10m3 0V5.5A1.5 1.5 0 0 1 15 4h2a1.5 1.5 0 0 1 1.5 1.5V10M4 18v3m16-3v3");
}

</style>
