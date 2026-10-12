<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><circle class="o5grrub_r"/><path class="t0u1xzm4y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:post-card-sharp" {...props}></Icon>
<style>
:global(.itxcm0bbl) {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

:global(.o5grrub_r) {
  cx: 7px;
  cy: 7px;
  r: 1.5px;
}

:global(.t0u1xzm4y) {
  d: path("M10.5 7H17M6.5 12h11m-11 4h7");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
