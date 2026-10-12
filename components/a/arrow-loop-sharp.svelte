<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cj_8r9bgf"/><path class="lz8bt9ehm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-loop-sharp" {...props}></Icon>
<style>
:global(.cj_8r9bgf) {
  d: path("M3.75 17c4 0 8.25-2.5 8.25-7.25a3 3 0 0 0-6 0C6 14.5 10.25 17 14.25 17H20");
}

:global(.lz8bt9ehm) {
  d: path("m16.75 13.5l3.5 3.5l-3.5 3.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
