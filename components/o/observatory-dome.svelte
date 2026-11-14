<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vynwjw15e"/><path class="pt0m3h17d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:observatory-dome" {...props}></Icon>
<style>
:global(.pt0m3h17d) {
  d: path("M10 16.5h4v5h-4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vynwjw15e) {
  d: path("M5 13a7 7 0 0 1 14 0M4 13h16v8.5H4Zm9-3l5.5-6");
}

</style>
