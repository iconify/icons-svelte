<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5un-6bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:phone-tripod" {...props}></Icon>
<style>
:global(.d5un-6bwr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.375 3h9.25A4.375 4.375 0 0 1 21 7.375v.75a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 8.125v-.75A4.375 4.375 0 0 1 7.375 3M5.5 21.5L12 15l6.5 6.5m-6.5-9v9M6 7.75h.01");
}

</style>
