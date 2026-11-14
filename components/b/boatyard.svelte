<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkg53fbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:boatyard" {...props}></Icon>
<style>
:global(.tkg53fbct) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10h16.5L17 15.5H5.5A1.5 1.5 0 0 1 4 14Zm6.5 0V3.5l6 6.5m-9 5.5v5m7-5v5M3 20.5h18");
}

</style>
