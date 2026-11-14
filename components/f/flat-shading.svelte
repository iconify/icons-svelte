<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oq2qjowwo"/><path class="ngjwxj32z"/><path class="yeqoigbkh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:flat-shading" {...props}></Icon>
<style>
:global(.ngjwxj32z) {
  d: path("M9.5 4L9 9.5l3 11");
}

:global(.oq2qjowwo) {
  d: path("M7 4h10l4 5.5l-9 11l-9-11ZM3 9.5h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yeqoigbkh) {
  fill: currentColor;
  d: path("M15 9.5h6l-9 11Z");
}

</style>
