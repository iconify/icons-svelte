<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0j2o_bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:friend-check" {...props}></Icon>
<style>
:global(.t0j2o_bry) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20c0-2.75 2.1-4.75 4.75-4.75S12 17.25 12 20c0 .6-.4 1-1 1H3.5c-.6 0-1-.4-1-1M4.25 7.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0m9.75 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M15.25 18L17 19.75l4-4");
}

</style>
