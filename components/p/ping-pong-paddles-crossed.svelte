<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idzl7abck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ping-pong-paddles-crossed" {...props}></Icon>
<style>
:global(.idzl7abck) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m11 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0m-4.25 2.75l8.25 8.25m-2.75-8.25L6.5 19.5");
}

</style>
