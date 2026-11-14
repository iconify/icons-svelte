<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vyk2jgbrd"/><path class="dygb1iwwr"/><path class="s_quhx2gi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cue-chalk" {...props}></Icon>
<style>
:global(.dygb1iwwr) {
  d: path("m3.5 7l8.5 4.5L20.5 7M12 11.5v10");
}

:global(.s_quhx2gi) {
  d: path("M8.5 7a3.5 1.75 0 1 0 7 0a3.5 1.75 0 1 0-7 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vyk2jgbrd) {
  d: path("M12 2.5L20.5 7v10L12 21.5L3.5 17V7Z");
}

</style>
