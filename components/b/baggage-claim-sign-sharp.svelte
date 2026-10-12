<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="sn8nvnb0h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:baggage-claim-sign-sharp" {...props}></Icon>
<style>
:global(.itxcm0bbl) {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

:global(.sn8nvnb0h) {
  d: path("M7.5 9h9v6h-9Zm2.75 0V6h3.5v3M6 18h12");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
