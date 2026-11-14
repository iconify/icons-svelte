<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awpxd4b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:friend-request-game" {...props}></Icon>
<style>
:global(.awpxd4b4j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0M3 21.5v-1C3 17 6 15 10 15c1.06 0 2.12.18 3.027.539M18.5 14v7M15 17.5h7");
}

</style>
