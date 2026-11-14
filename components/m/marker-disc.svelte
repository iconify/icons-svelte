<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwzf82bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:marker-disc" {...props}></Icon>
<style>
:global(.dwzf82bfe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5c0-7.5 19-7.5 19 0c0 3-19 3-19 0M4 18h16M9 10h6");
}

</style>
