<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rwdy2vd9c"/><path class="k7eugebie"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fez-sharp" {...props}></Icon>
<style>
:global(.k7eugebie) {
  d: path("M11.25 7.5c2-3.5 7-4 8.75-1V11m-.75 0h1.5l.5 3h-2.5Z");
}

:global(.rwdy2vd9c) {
  d: path("M7.25 7.5h8.25l.17 1.24l1.41 10.27l.17 1.24h-13l.17-1.24L5.83 8.74L6 7.5zM4.75 17h12");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
