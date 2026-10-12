<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="d8mt2_n-r"/><path class="lrtf_8vxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ringed-planet-sharp" {...props}></Icon>
<style>
:global(.d8mt2_n-r) {
  cx: 12px;
  cy: 12px;
  r: 6.25px;
}

:global(.lrtf_8vxb) {
  d: path("M18.17 6.86a9.75 3.25-25.71 1 1-14.03 6.76");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
