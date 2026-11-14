<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sn3_yybhy"/><path class="teegcvsqy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dpad-up" {...props}></Icon>
<style>
:global(.sn3_yybhy) {
  d: path("M8.5 2.5h7v6h6v7h-6v6h-7v-6h-6v-7h6Z");
}

:global(.teegcvsqy) {
  fill: currentColor;
  d: path("M8.5 2.5h7v6h-7Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
