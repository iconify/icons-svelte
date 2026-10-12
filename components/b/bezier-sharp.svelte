<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uhkhlvkje"/><circle class="g3jvdsbwi"/><circle class="zo34uu--r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bezier-sharp" {...props}></Icon>
<style>
:global(.g3jvdsbwi) {
  cx: 4.25px;
  cy: 9px;
  r: 1.5px;
}

:global(.uhkhlvkje) {
  d: path("M10.25 10.75C8 11.25 6 14 5.25 21.25m8.5-10.5c2.25.5 4.25 3.25 5 10.5M5.75 9h4.5m3.5 0h4.5m-8-1.75h3.5v3.5h-3.5z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zo34uu--r) {
  cx: 19.75px;
  cy: 9px;
  r: 1.5px;
}

</style>
