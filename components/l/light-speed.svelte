<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko2jk7bch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:light-speed" {...props}></Icon>
<style>
:global(.ko2jk7bch) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 12H21m-4-4l4 4l-4 4M2.5 12h3M3 7h10M3 17h10");
}

</style>
