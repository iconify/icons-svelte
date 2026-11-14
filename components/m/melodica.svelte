<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws6n6-b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:melodica" {...props}></Icon>
<style>
:global(.ws6n6-b4c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 7h8a3.5 3.5 0 0 1 3.5 3.5A3.5 3.5 0 0 1 18 14h-8a3.5 3.5 0 0 1-3.5-3.5A3.5 3.5 0 0 1 10 7M6.5 9.5c-2.5 0-4 1.5-4 4V17m7-6v3m3-3v3m3-3v3m3-3v3");
}

</style>
