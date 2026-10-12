<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ysa2-oqog"/><path class="u5gto-b8u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mirror-hand-sharp" {...props}></Icon>
<style>
:global(.u5gto-b8u) {
  d: path("M10.75 13.25h2.5v8h-2.5zm-2-4.75a3.25 3 0 0 1 3.25-3");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ysa2-oqog) {
  d: path("M12 3a6 5.5 0 1 1 0 11a6 5.5 0 1 1 0-11Z");
}

</style>
