<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5ekuhbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ear-defenders-lab" {...props}></Icon>
<style>
:global(.q5ekuhbxo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 10a6.5 6.5 0 0 1 13 0m-13 0za3 3 0 0 1 3 3v4.5a3 3 0 0 1-3 3a3 3 0 0 1-3-3V13a3 3 0 0 1 3-3m13 0za3 3 0 0 1 3 3v4.5a3 3 0 0 1-3 3a3 3 0 0 1-3-3V13a3 3 0 0 1 3-3");
}

</style>
