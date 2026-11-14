<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c79vntd-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gas-tank-storage" {...props}></Icon>
<style>
:global(.c79vntd-r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 9.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m2.25 5l-1.5 7m10-7l1.5 7M5.5 9.5h13");
}

</style>
