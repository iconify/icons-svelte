<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="eoenbp1iq"/><path class="u8xnuhq8x"/><path class="i9lue-apj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:praying-person-sharp" {...props}></Icon>
<style>
:global(.eoenbp1iq) {
  cx: 9.5px;
  cy: 4.75px;
  r: 2px;
}

:global(.i9lue-apj) {
  d: path("m9.5 10.5l3 3.25L14.75 9");
}

:global(.u8xnuhq8x) {
  d: path("M9.5 8.75v9H19v3.5H5.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
