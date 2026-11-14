<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq6zqebur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lawn-top-dressing" {...props}></Icon>
<style>
:global(.pq6zqebur) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20h19m-18 0l2-5l2 5l2-5l2 5l2-5l2 5l2-5l2 5l1-2.5M5 10.5h.01m4.74 0h.01m4.49 0h.01m4.74 0h.01");
}

</style>
