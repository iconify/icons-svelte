<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gfwfgvbhl"/><path class="imq4_mabh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:reduce-transparency-sharp" {...props}></Icon>
<style>
:global(.gfwfgvbhl) {
  d: path("M10.5 10.5h10.75v10.75H10.5z");
}

:global(.imq4_mabh) {
  d: path("M2.75 2.75h12v12h-12zM6 9.5L9.5 6M6 13l7-7");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
