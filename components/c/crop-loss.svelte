<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw1nfvp_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:crop-loss" {...props}></Icon>
<style>
:global(.xw1nfvp_z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 21.5v-17M8 19c-2.5 0-4-1.5-4-4c2.5 0 4 1.5 4 4m0 0c2.5 0 4-1.5 4-4c-2.5 0-4 1.5-4 4m0-6.5c-2.5 0-4-1.5-4-4c2.5 0 4 1.5 4 4m0 0c2.5 0 4-1.5 4-4c-2.5 0-4 1.5-4 4m10 2v7m-3-3l3 3l3-3");
}

</style>
