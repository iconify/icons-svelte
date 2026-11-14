<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x29zynbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:playground-hotel" {...props}></Icon>
<style>
:global(.x29zynbfi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4h12M6 4L3 21M18 4l3 17M10 4v10.5M14 4v10.5m-5 0h6");
}

</style>
