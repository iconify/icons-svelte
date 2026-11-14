<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vamoo_bvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ironing" {...props}></Icon>
<style>
:global(.vamoo_bvj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5c.5-4.5 3-7.5 7-7.5H20v7.5ZM11 10V8a2 2 0 0 1 2-2h7v4M2.5 21h19");
}

</style>
