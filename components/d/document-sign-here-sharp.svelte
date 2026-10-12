<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rh2140hgr"/><path class="fxipxrb3q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:document-sign-here-sharp" {...props}></Icon>
<style>
:global(.fxipxrb3q) {
  d: path("M13.75 2.75v5.5h5.5m-11 3.5h5m-5 5.75c.75-2 1.75-3.25 2.5-2.5s-.5 2.5.5 2.5s1.25-1.5 2-1.5s.5 1 1.5 1H16");
}

:global(.rh2140hgr) {
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
