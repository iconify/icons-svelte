<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ixrllqbhh"/><path class="o-naylwhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:frankenstein-bolt" {...props}></Icon>
<style>
:global(.ixrllqbhh) {
  d: path("M5.5 3h13v17.5h-13Zm-3 9.5h3v3h-3Zm16 0h3v3h-3Z");
}

:global(.o-naylwhk) {
  d: path("M5.5 7.5L8.75 9L12 7.5L15.25 9l3.25-1.5m-9 5.25h.01m4.99 0h.01m-5.01 4h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
