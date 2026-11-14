<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0aj82b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:deceleration" {...props}></Icon>
<style>
:global(.w0aj82b-p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.1 15.5H8V4h11.5v7.7M2.5 7h3.25M2.5 11h3.25M18 14.5V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>
