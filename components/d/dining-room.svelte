<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgua_g5qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dining-room" {...props}></Icon>
<style>
:global(.bgua_g5qd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 9.5h9a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-9a1 1 0 0 1-1-1a1 1 0 0 1 1-1m1.5 2v10m6-10v10M3 7.5v14M3 15h3v6.5m15-14v14m0-6.5h-3v6.5");
}

</style>
