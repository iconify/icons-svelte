<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z98devblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ice-cream-sundae" {...props}></Icon>
<style>
:global(.z98devblm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 10h14c0 4.5-3 7-7 7s-7-2.5-7-7m7 7v3.5m-4 0h8M7 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m5 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
