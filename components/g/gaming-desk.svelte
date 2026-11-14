<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycn_7cb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gaming-desk" {...props}></Icon>
<style>
:global(.ycn_7cb2r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3.5q8-1.5 16 0V11q-8-1.5-16 0Zm8 6.75v4.25m-9.5 0h19m-17 0v7m15-7v7");
}

</style>
