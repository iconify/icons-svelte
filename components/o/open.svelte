<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vemt00jxu"/><path class="wa_ebigtw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:open" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vemt00jxu) {
  d: path("M3.5 19V6.5A1.5 1.5 0 0 1 5 5h4l2 2h6a1.5 1.5 0 0 1 1.5 1.5v3");
}

:global(.wa_ebigtw) {
  d: path("m3.5 19l3.25-7.5H21.5L18.25 19Z");
}

</style>
