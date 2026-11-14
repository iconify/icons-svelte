<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbuhgkxdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fewest-changes" {...props}></Icon>
<style>
:global(.vbuhgkxdp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 19.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m14.5-14.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-11 13L10 14m4-4l3.75-3.75M9.25 12a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

</style>
