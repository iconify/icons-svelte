<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tog69bbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hockey-jersey" {...props}></Icon>
<style>
:global(.tog69bbqi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3L3 6.5L5 11l2-1v11h10V10l2 1l2-4.5L16 3c-1 2-2.5 2.5-4 2.5S9 5 8 3M7 14h10M7 17h10");
}

</style>
