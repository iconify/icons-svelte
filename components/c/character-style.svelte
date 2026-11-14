<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oda4a2bll"/><path class="f5nxd8mmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:character-style" {...props}></Icon>
<style>
:global(.f5nxd8mmi) {
  d: path("m6.25 16.5l3-9l3 9M7.5 13.25H11m4-4.75h3m-3 7h3");
}

:global(.oda4a2bll) {
  d: path("M3 3.5h18v17H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
