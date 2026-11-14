<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkvzwsb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dust-mop" {...props}></Icon>
<style>
:global(.mkvzwsb8d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.5 2.5L12 15m-6.5 0h13a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2a2 2 0 0 1 2-2M7 19v2.5m5-2.5v2.5m5-2.5v2.5");
}

</style>
