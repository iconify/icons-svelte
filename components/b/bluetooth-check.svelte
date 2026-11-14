<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyj82mb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bluetooth-check" {...props}></Icon>
<style>
:global(.oyj82mb0d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 7.5l9.5 8.5L8 20.5v-17L12.5 8L3 16.5M14.75 18l2 2L21 15.75");
}

</style>
