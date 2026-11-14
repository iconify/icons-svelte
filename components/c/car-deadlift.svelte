<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmnrjlb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:car-deadlift" {...props}></Icon>
<style>
:global(.wmnrjlb0n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 14.5V11q0-1.5 1.5-1.5l1.5-3.5h3.5l1.5 3.5q1.5 0 1.5 1.5v3.5M3.5 10za1 1 0 0 1 1 1v7a1 1 0 0 1-1 1a1 1 0 0 1-1-1v-7a1 1 0 0 1 1-1m17 0za1 1 0 0 1 1 1v7a1 1 0 0 1-1 1a1 1 0 0 1-1-1v-7a1 1 0 0 1 1-1m-16 4.5h15");
}

</style>
