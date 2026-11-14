<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq-_r3b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hurling-stick" {...props}></Icon>
<style>
:global(.sq-_r3b8y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 2.5L13 13m0 0c0 4-2 8-6 8.5c-2.5.25-3-2-1.5-3.5c2-2 4-3 7.5-5m3.25 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
