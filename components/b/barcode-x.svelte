<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a090j-bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:barcode-x" {...props}></Icon>
<style>
:global(.a090j-bzs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5v15m3-15v15m3-15v15m3-15V12m3 3.5l5 5m0-5l-5 5");
}

</style>
