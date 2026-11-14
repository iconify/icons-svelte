<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu7hu_cyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:badminton-net" {...props}></Icon>
<style>
:global(.zu7hu_cyu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21V4h19v17m-19-8.5h19m-19-4.25h19M8.75 4v8.5m6.5-8.5v8.5");
}

</style>
