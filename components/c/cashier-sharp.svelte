<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="wv5f_1brg"/><path class="cf5bjz6ju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cashier-sharp" {...props}></Icon>
<style>
:global(.cf5bjz6ju) {
  d: path("M5.75 14.25a6.25 4 0 0 1 12.5 0Zm-3 0h18.5v7H2.75zm6.75 3.5h5");
}

:global(.wv5f_1brg) {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
