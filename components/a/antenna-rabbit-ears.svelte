<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otonbcc5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:antenna-rabbit-ears" {...props}></Icon>
<style>
:global(.otonbcc5q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 15h9a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-9a3 3 0 0 1-3-3a3 3 0 0 1 3-3m2.5 0L6 4m8 11l4-11m-2 14h.01");
}

</style>
