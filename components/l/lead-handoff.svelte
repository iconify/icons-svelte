<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjv8fuman"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lead-handoff" {...props}></Icon>
<style>
:global(.jjv8fuman) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 5.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M2.5 15c0-2.5 1.75-4 4-4s4 1.5 4 4m4.25-9.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M13.5 15c0-2.5 1.75-4 4-4s4 1.5 4 4M5 19.5h14m-2.25-2.25L19 19.5l-2.25 2.25");
}

</style>
