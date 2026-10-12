<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pylbxfbox"/><path class="ccxivbcno"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:doghouse-sharp" {...props}></Icon>
<style>
:global(.ccxivbcno) {
  d: path("M9 21.25V16a3 3 0 0 1 6 0v5.25m-4.5-9.5h3");
}

:global(.pylbxfbox) {
  d: path("m12.79 4.12l6.67 5.26l.79.62h-1.5v11.25H5.25V10h-1.5l.79-.62l6.67-5.26l.79-.62z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
