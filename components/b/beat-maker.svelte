<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="frvc0ccmu"/><path class="n68k7vb-x"/><path class="b4dvasppn"/><path class="fnccr8vti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:beat-maker" {...props}></Icon>
<style>
:global(.b4dvasppn) {
  fill: currentColor;
  d: path("M14 8.75h4v4h-4Z");
}

:global(.fnccr8vti) {
  d: path("M6 15.5h4v4H6Zm8 0h4v4h-4Z");
}

:global(.frvc0ccmu) {
  d: path("M2.5 2.5h19v19h-19Zm3.5 3h4.5");
}

:global(.n68k7vb-x) {
  d: path("M6 8.75h4v4H6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
