<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sn3_yybhy"/><path class="zphf7sbzb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dpad-up" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sn3_yybhy) {
  d: path("M8.5 2.5h7v6h6v7h-6v6h-7v-6h-6v-7h6Z");
}

:global(.zphf7sbzb) {
  fill: currentColor;
  d: path("M10 2.5h4A1.5 1.5 0 0 1 15.5 4v3A1.5 1.5 0 0 1 14 8.5h-4A1.5 1.5 0 0 1 8.5 7V4A1.5 1.5 0 0 1 10 2.5");
}

</style>
