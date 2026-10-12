<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="kvk85nbvi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:detour-sign-sharp" {...props}></Icon>
<style>
:global(.itxcm0bbl) {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

:global(.kvk85nbvi) {
  d: path("M6.25 17.5h4V8.75h7m-2.5-2.5l2.5 2.5l-2.5 2.5M14 17.5h3.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
