<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="dzf8fh4so"/><circle class="i2w7l1bsp"/><circle class="hv7t5-70z"/><circle class="usbadzy3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fearful-sharp" {...props}></Icon>
<style>
:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.dzf8fh4so) {
  d: path("M9.5 4.5v2M12 4.25v2m2.5-1.75v2");
}

:global(.hv7t5-70z) {
  cx: 15px;
  cy: 10.5px;
  r: 1.25px;
}

:global(.i2w7l1bsp) {
  cx: 9px;
  cy: 10.5px;
  r: 1.25px;
}

:global(.usbadzy3d) {
  cx: 12px;
  cy: 16px;
  r: 1.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
