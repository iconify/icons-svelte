<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2d7p7p1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:barcode-check" {...props}></Icon>
<style>
:global(.l2d7p7p1n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5v15m3-15v15m3-15v15m3-15V12m2.25 6l2 2L21 15.75");
}

</style>
