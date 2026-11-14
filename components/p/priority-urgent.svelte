<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4ph-4b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:priority-urgent" {...props}></Icon>
<style>
:global(.t4ph-4b8r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5v19m0-18h14.5l-3 5.75l3 5.75H5m6-8.75v3.5m0 2.75h.01");
}

</style>
