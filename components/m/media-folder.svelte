<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zd9fbdclh"/><path class="qyrdhob1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:media-folder" {...props}></Icon>
<style>
:global(.qyrdhob1o) {
  d: path("m9.75 10.25l5.5 3l-5.5 3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zd9fbdclh) {
  d: path("M2.5 7a2 2 0 0 1 2-2H9l2 2.5h8.5a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2Z");
}

</style>
