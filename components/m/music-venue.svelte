<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d5p848ylk"/><path class="idrit8bor"/><path class="nh1tkhicc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:music-venue" {...props}></Icon>
<style>
:global(.d5p848ylk) {
  d: path("m3.5 9.5l8.5-7l8.5 7V21h-17Z");
}

:global(.idrit8bor) {
  fill: currentColor;
  d: path("M8.5 16.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.nh1tkhicc) {
  d: path("M12 16.5v-7m0 0l3.5 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
