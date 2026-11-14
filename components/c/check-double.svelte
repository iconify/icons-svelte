<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xongtzbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:check-double" {...props}></Icon>
<style>
:global(.xongtzbhg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 12.5l4 4l8-8m-3 7l1.25 1.25L21 8.5");
}

</style>
