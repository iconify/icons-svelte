<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf2w45x1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:contact-opt-in" {...props}></Icon>
<style>
:global(.sf2w45x1n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 7a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0M3 20.5c0-3.75 3.25-6 7-6c1.541 0 2.887.31 4.04.794M14.75 18l2 2L21 15.75");
}

</style>
