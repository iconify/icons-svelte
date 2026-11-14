<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-g7bobvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bluetooth-searching" {...props}></Icon>
<style>
:global(.a-g7bobvb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 7.5l9.5 8.5L8 20.5v-17L12.5 8L3 16.5m12 1a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m4.25 1.75L21 21");
}

</style>
