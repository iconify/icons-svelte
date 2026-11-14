<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz7nz_b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:molecule-chain" {...props}></Icon>
<style>
:global(.dz7nz_b7o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15a2 2 0 1 0 4 0a2 2 0 1 0-4 0m5-6a2 2 0 1 0 4 0a2 2 0 1 0-4 0m5 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0m5-6a2 2 0 1 0 4 0a2 2 0 1 0-4 0M5.75 13.5l2.5-3m2.5 0l2.5 3m2.5 0l2.5-3");
}

</style>
