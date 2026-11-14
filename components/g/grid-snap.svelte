<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwk0f7bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:grid-snap" {...props}></Icon>
<style>
:global(.fwk0f7bcl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5v19m-5-14h19m-5-5v8.25m-14 5.75h8.25m3 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

</style>
