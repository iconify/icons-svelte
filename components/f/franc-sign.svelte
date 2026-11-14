<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwmahybsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:franc-sign" {...props}></Icon>
<style>
:global(.lwmahybsb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 4H8.5v16m0-8.5H16M5 16h7.5");
}

</style>
