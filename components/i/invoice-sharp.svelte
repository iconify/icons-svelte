<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rh2140hgr"/><path class="p6155gmjl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:invoice-sharp" {...props}></Icon>
<style>
:global(.p6155gmjl) {
  d: path("M13.75 2.75v5.5h5.5m-11 0h2.5M8.25 12h3.5m2.75 0h1.25m-7.5 3h3.5m2.75 0h1.25m-3 3.25h3");
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
