<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu602xbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:popover-arrow" {...props}></Icon>
<style>
:global(.vu602xbvr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5A2.5 2.5 0 0 1 5 7h4l3-3.5L15 7h4a2.5 2.5 0 0 1 2.5 2.5V18a2.5 2.5 0 0 1-2.5 2.5H5A2.5 2.5 0 0 1 2.5 18Zm4 2.5h11m-11 4H13");
}

</style>
