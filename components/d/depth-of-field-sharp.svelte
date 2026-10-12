<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qmnyfnbre"/><circle class="cgeon5wki"/><path class="r0i38ebaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:depth-of-field-sharp" {...props}></Icon>
<style>
:global(.cgeon5wki) {
  cx: 13.71px;
  cy: 10.29px;
  r: 2.5px;
}

:global(.qmnyfnbre) {
  d: path("M11.5 16.5a4 4 0 1 1-8 0a4 4 0 1 1 8 0");
}

:global(.r0i38ebaj) {
  d: path("M20.5 5.5a2 2 0 1 1-4 0a2 2 0 1 1 4 0");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
