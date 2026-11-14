<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjvr-vdsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:incense" {...props}></Icon>
<style>
:global(.wjvr-vdsy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 20.5L14.5 10M4 20.5h16m-4-13c1.5-1.5-1-2.75.5-5m3 7.5c1.5-1.5-1-2.75.5-5");
}

</style>
