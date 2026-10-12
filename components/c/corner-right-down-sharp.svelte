<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zatjtebrs"/><path class="grlcs-vwr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:corner-right-down-sharp" {...props}></Icon>
<style>
:global(.grlcs-vwr) {
  d: path("m11 15.5l3.75 3.75l3.75-3.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zatjtebrs) {
  d: path("M4.25 4.25h10.5v15");
}

</style>
