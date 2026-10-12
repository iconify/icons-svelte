<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dc3o2gb9z"/><path class="frsaaq3rt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:franchise-store-sharp" {...props}></Icon>
<style>
:global(.dc3o2gb9z) {
  d: path("M4.5 9h15v12h-15zM3 4h18v5H3zm6 0v5m6-5v5");
}

:global(.frsaaq3rt) {
  d: path("M10 21v-6h4v6");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
