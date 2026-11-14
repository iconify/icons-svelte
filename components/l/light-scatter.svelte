<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwutgfx3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:light-scatter" {...props}></Icon>
<style>
:global(.qwutgfx3e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h5m0 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m8 0h6m-7.25-3.5l4.25-3.75M14.25 15.5l4.25 3.75");
}

</style>
