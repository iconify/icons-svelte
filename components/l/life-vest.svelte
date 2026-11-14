<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxpnqmcpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:life-vest" {...props}></Icon>
<style>
:global(.mxpnqmcpo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4h4l2 4l2-4h4l1 16.5H5Zm6 4v12.5M5 14h14");
}

</style>
