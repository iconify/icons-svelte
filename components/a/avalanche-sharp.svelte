<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="obo5o2gtj"/><path class="cs-d-7bky"/><circle class="iva9qxbgz"/><circle class="ne7htm4pe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:avalanche-sharp" {...props}></Icon>
<style>
:global(.cs-d-7bky) {
  d: path("M6.4 8.4L8 9.75l1.25-1l1.25 1l1.4-1.2");
}

:global(.iva9qxbgz) {
  cx: 18.5px;
  cy: 18.75px;
  r: 2.5px;
}

:global(.ne7htm4pe) {
  cx: 12.25px;
  cy: 20px;
  r: 1.25px;
}

:global(.obo5o2gtj) {
  d: path("m9.58 3.8l6.34 11.4l.58 1.05H2.75l.5-1.09L8.5 3.84L9 2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
