<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2e91bc2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:playback-1x" {...props}></Icon>
<style>
:global(.g2e91bc2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 7.5l3.5-3v15m3.5-8.5l6.5 6.5m0-6.5l-6.5 6.5");
}

</style>
