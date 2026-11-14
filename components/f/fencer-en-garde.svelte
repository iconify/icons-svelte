<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyla6wmba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fencer-en-garde" {...props}></Icon>
<style>
:global(.kyla6wmba) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 4.75a4.6 4.6 0 0 1-6.5 6.5Zm-8.5-2L8 8m3.25 3.25L21 21");
}

</style>
