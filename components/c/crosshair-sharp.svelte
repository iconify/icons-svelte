<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="f_362pbxn"/><path class="zt7gkkpde"/><circle class="lf940mbnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:crosshair-sharp" {...props}></Icon>
<style>
:global(.f_362pbxn) {
  cx: 12px;
  cy: 12px;
  r: 7px;
}

:global(.lf940mbnz) {
  cx: 12px;
  cy: 12px;
  r: 1.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zt7gkkpde) {
  d: path("M12 2.75v5.5m0 7.5v5.5M2.75 12h5.5m7.5 0h5.5");
}

</style>
