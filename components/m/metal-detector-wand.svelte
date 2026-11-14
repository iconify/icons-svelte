<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mx_i7_2qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:metal-detector-wand" {...props}></Icon>
<style>
:global(.mx_i7_2qr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 18.5a7 3 0 1 0 14 0a7 3 0 1 0-14 0M4 2.5l9.5 13M7 6.75l-2.75 2");
}

</style>
