<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rh2140hgr"/><path class="rzhjezkpv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:code-xml-sharp" {...props}></Icon>
<style>
:global(.rh2140hgr) {
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

:global(.rzhjezkpv) {
  d: path("M13.75 2.75v5.5h5.5M10 11.75L7.75 14.5L10 17.25m4-5.5l2.25 2.75L14 17.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
