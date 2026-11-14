<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nora7_bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mesh-node-offline" {...props}></Icon>
<style>
:global(.nora7_bbl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.75 7.25l-4.5 8.5m7-8.5l4 8M7.5 18h8m-6-13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-7 13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m13 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0m5-2l-4 4");
}

</style>
