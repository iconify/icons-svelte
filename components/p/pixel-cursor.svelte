<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj6j9nbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pixel-cursor" {...props}></Icon>
<style>
:global(.pj6j9nbel) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 3v15.5h2.5V16h2.5v2.5h2.5V21h5v-2.5h-2.5V16h2.5v-2.5h-2.5V11h-2.5V8.5h-2.5V6h-2.5V3Zm5 13h5");
}

</style>
