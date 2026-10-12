<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hk09bvr2w"/><path class="pbu2b0thw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hospital-sharp" {...props}></Icon>
<style>
:global(.hk09bvr2w) {
  d: path("M3.75 21.25V11H7V2.75h10V11h3.25v10.25ZM12 5.5V10M9.75 7.75h4.5");
}

:global(.pbu2b0thw) {
  d: path("M10.25 21.25V17h3.5v4.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
