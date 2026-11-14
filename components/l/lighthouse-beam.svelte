<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzz1vicqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lighthouse-beam" {...props}></Icon>
<style>
:global(.bzz1vicqo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21L6 9.5h4L12 21ZM6 9.5V6l2-2.5L10 6v3.5m3-4l8.5-2.75M13 9l8.5 2.75");
}

</style>
