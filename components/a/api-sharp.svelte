<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="w8aau4nfz"/><circle class="hjru5mbwv"/><circle class="n2he7vj4w"/><circle class="dsbyipbjc"/><circle class="hvjhicbar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:api-sharp" {...props}></Icon>
<style>
:global(.dsbyipbjc) {
  cx: 4px;
  cy: 12px;
  r: 1.25px;
}

:global(.hjru5mbwv) {
  cx: 12px;
  cy: 4px;
  r: 1.25px;
}

:global(.hvjhicbar) {
  cx: 20px;
  cy: 12px;
  r: 1.25px;
}

:global(.n2he7vj4w) {
  cx: 12px;
  cy: 20px;
  r: 1.25px;
}

:global(.w8aau4nfz) {
  d: path("M9.25 9.25h5.5v5.5h-5.5zm2.75 0v-3m0 8.5v3M9.25 12h-3m8.5 0h3");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
