<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="irex6lbbg"/><path class="w0htgd6_b"/><path class="eeils9ble"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:person-presenting-sharp" {...props}></Icon>
<style>
:global(.eeils9ble) {
  d: path("m12.75 8.25l2-2l1.5 1.5l2.5-2.5m-3 5.5v10.5");
}

:global(.irex6lbbg) {
  cx: 5.5px;
  cy: 6.25px;
  r: 2px;
}

:global(.w0htgd6_b) {
  d: path("M5.5 10.75v5m-1.75 5.5l1.75-5.5l1.75 5.5M5.5 12l2.75-2m2-7.25h11v8h-11z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
