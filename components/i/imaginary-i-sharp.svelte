<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wr063mk4n"/><circle class="ht4-d0djo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:imaginary-i-sharp" {...props}></Icon>
<style>
:global(.ht4-d0djo) {
  cx: 12px;
  cy: 5.5px;
  r: 1.5px;
}

:global(.wr063mk4n) {
  d: path("M9.25 10H12v10m-3.25 0h6.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
