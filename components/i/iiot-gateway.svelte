<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3zuqib3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:iiot-gateway" {...props}></Icon>
<style>
:global(.f3zuqib3r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.7 14H2.5V4h19v7.3M6.5 9h.01M10 9h.01M18 21h.01M16 17.536a4 4 0 0 1 4 0m-5.75-3.031a7.5 7.5 0 0 1 7.5 0");
}

</style>
