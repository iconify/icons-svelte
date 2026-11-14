<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xmh1vmjaj"/><path class="sev4z9b1w"/><path class="me0yc5b4p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:active-passive" {...props}></Icon>
<style>
:global(.me0yc5b4p) {
  d: path("M5.75 17.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.sev4z9b1w) {
  fill: currentColor;
  d: path("M5.75 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xmh1vmjaj) {
  d: path("M3 2.5h18v8H3Zm0 10.75h18v8H3Z");
}

</style>
