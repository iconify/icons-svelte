<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l9bjbn4cy"/><path class="f5drlus7q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:player-contract" {...props}></Icon>
<style>
:global(.f5drlus7q) {
  d: path("M8 15.25c1-2.75 2.5-2.75 2.5-.75c0 1.5 2-1.5 3.25-.5H16m-8 4.25h8");
}

:global(.l9bjbn4cy) {
  d: path("M5 4.5a2 2 0 0 1 2-2h7.5L19 7v12.5a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2ZM8 7h4.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
