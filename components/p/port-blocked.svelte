<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz86g2djq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:port-blocked" {...props}></Icon>
<style>
:global(.fz86g2djq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3.5h13A1.5 1.5 0 0 1 20 5v5.5a1.5 1.5 0 0 1-1.5 1.5H16v2.5H8V12H5.5A1.5 1.5 0 0 1 4 10.5V5a1.5 1.5 0 0 1 1.5-1.5m2.5 2V8m3-2.5V8m3-2.5V8m1.5 7.5l5 5m0-5l-5 5");
}

</style>
