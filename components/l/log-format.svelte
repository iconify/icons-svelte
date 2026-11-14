<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rp5z-2b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:log-format" {...props}></Icon>
<style>
:global(.rp5z-2b-t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5h18M3 10h14M3 15h8m5-1.25a1 1 0 0 0-1 1v2a1 1 0 0 1-1 1a1 1 0 0 1 1 1v2a1 1 0 0 0 1 1m4-8a1 1 0 0 1 1 1v2a1 1 0 0 0 1 1a1 1 0 0 0-1 1v2a1 1 0 0 1-1 1");
}

</style>
