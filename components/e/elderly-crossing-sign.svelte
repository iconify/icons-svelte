<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dmx6drbsd"/><path class="b665n4b7x"/><path class="ox8thhbkk"/><path class="kptcbybdf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:elderly-crossing-sign" {...props}></Icon>
<style>
:global(.b665n4b7x) {
  d: path("M5.25 6.25Q4 9.5 4.5 13.25L2.75 21m1.75-7.75L6.25 21m10-16.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.dmx6drbsd) {
  d: path("M4.75 4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.kptcbybdf) {
  d: path("m16 9.5l4.5 2.5v9");
}

:global(.ox8thhbkk) {
  d: path("M16.75 6.25q-1.25 3.25-.75 7L14.25 21M16 13.25L17.75 21M4.5 9.5L9 12v9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
