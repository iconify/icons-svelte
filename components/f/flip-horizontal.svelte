<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwg0g_26l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flip-horizontal" {...props}></Icon>
<style>
:global(.kwg0g_26l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12v4.75a1.75 1.75 0 0 1-1.75 1.75H5.735a1.75 1.75 0 0 1-1.589-2.483l2.13-4.615A1.428 1.428 0 0 1 9 12m6 0v4.75a1.75 1.75 0 0 0 1.75 1.75h1.515a1.75 1.75 0 0 0 1.589-2.483l-2.13-4.615A1.428 1.428 0 0 0 15 12m-3-9v18");
}

</style>
