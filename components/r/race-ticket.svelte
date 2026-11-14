<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yyb7axbxh"/><path class="jfyglrz3p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:race-ticket" {...props}></Icon>
<style>
:global(.jfyglrz3p) {
  fill: currentColor;
  d: path("M4.5 5h3v3.5h-3Zm6 0h3v3.5h-3Zm6 0h3v3.5h-3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yyb7axbxh) {
  d: path("M4.5 5h15a2 2 0 0 1 2 2v3a2 2 0 0 0 0 4v3a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2v-3a2 2 0 0 0 0-4V7a2 2 0 0 1 2-2Zm-2 3.5h19");
}

</style>
