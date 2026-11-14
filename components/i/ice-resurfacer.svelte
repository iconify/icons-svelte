<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqryylbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ice-resurfacer" {...props}></Icon>
<style>
:global(.aqryylbrf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8h8a3.5 3.5 0 0 1 3.5 3.5V13a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 13v-1.5A3.5 3.5 0 0 1 6 8m6.25-3.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M4.5 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6-7.5h3.5v5");
}

</style>
