<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d05i8nr0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pixel-coin" {...props}></Icon>
<style>
:global(.d05i8nr0b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3h8v2.5h2.5V8H21v8h-2.5v2.5H16V21H8v-2.5H5.5V16H3V8h2.5V5.5H8Zm4 5.5v7");
}

</style>
