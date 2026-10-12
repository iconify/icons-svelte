<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="p_rn8pbth"/><path class="m-qubib1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:loader-sharp" {...props}></Icon>
<style>
:global(.m-qubib1j) {
  d: path("M13 5.75h8.25M13 9.25h5m-15.25 6.5h18.5m-18.5 4h12");
}

:global(.p_rn8pbth) {
  cx: 6.5px;
  cy: 7.5px;
  r: 3.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
