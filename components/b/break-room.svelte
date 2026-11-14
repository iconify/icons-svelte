<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnv26tbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:break-room" {...props}></Icon>
<style>
:global(.fnv26tbyv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 11V9a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v2M6 11h12a3 3 0 0 1 3 3a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3a3 3 0 0 1 3-3m-.5 6v2.5m13-2.5v2.5");
}

</style>
