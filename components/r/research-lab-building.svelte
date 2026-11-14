<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcpy_1ese"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:research-lab-building" {...props}></Icon>
<style>
:global(.lcpy_1ese) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5v6a6.5 6.5 0 1 0 4 0v-6m-5.5 0h7M5.5 15h13");
}

</style>
