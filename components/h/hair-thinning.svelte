<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vf52lccad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hair-thinning" {...props}></Icon>
<style>
:global(.vf52lccad) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3C3.5 9 8.5 14 6 21m4.5-18C8 9 13 14 10.5 21M15 3c-2.5 5 2 6.5 0 10m3 1.5v7m-3-3l3 3l3-3");
}

</style>
