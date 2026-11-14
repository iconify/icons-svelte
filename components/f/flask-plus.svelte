<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr51sksze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flask-plus" {...props}></Icon>
<style>
:global(.dr51sksze) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3.5V9l-5 9.5q-1 2 1.25 2h7.531m2.286-7.573L14 9V3.5m-5.5 0h7M18 15v6m-3-3h6");
}

</style>
