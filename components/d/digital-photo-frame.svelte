<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hneliqdkn"/><path class="ec9vtvbok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:digital-photo-frame" {...props}></Icon>
<style>
:global(.ec9vtvbok) {
  d: path("m2.5 16l6-6l6 6l2.25-2.25l4.75 4.75m-6-10h.01");
}

:global(.hneliqdkn) {
  d: path("M2.5 4h19v16h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
