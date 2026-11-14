<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_o3ksb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:beamed-sixteenths" {...props}></Icon>
<style>
:global(.a_o3ksb1f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 18.5a3 2.25 0 1 0 6 0a3 2.25 0 1 0-6 0m10 0a3 2.25 0 1 0 6 0a3 2.25 0 1 0-6 0m-4 0V4m10 14.5V4M10 4h10M10 7.5h10");
}

</style>
