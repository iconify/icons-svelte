<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzgrrd6dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:moon-rain" {...props}></Icon>
<style>
:global(.uzgrrd6dh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 9.5a6 6 0 1 1-7-7a7 7 0 0 0 7 7m-10 8l-1 4m5-4l-1 4m5-4l-1 4");
}

</style>
