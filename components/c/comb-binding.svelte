<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d4_a89bmh"/><path class="aof00x69w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:comb-binding" {...props}></Icon>
<style>
:global(.aof00x69w) {
  d: path("M6 2.5h2.5v5H6Zm4.75 0h2.5v5h-2.5Zm4.75 0H18v5h-2.5Z");
}

:global(.d4_a89bmh) {
  d: path("M4.5 4.5h15V19h-15Zm2 17h11");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
