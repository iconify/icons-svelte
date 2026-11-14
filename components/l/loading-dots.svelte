<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lu7_oqb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:loading-dots" {...props}></Icon>
<style>
:global(.lu7_oqb_b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-7 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m14 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
