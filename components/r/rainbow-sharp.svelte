<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ekl9uqbsh"/><path class="nxprb0bnr"/><path class="j2sf4ozhl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rainbow-sharp" {...props}></Icon>
<style>
:global(.ekl9uqbsh) {
  d: path("M2.75 16.75a9.25 9.25 0 0 1 18.5 0");
}

:global(.j2sf4ozhl) {
  d: path("M9.25 16.75a2.75 2.75 0 0 1 5.5 0");
}

:global(.nxprb0bnr) {
  d: path("M6 16.75a6 6 0 0 1 12 0");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
