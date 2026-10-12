<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u8_vc4yqr"/><circle class="sz7o-pbpi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:camera-bag-sharp" {...props}></Icon>
<style>
:global(.sz7o-pbpi) {
  cx: 12px;
  cy: 16.25px;
  r: 2px;
}

:global(.u8_vc4yqr) {
  d: path("M2.75 8.25h18.5v12.5H2.75zm6 0v-3.5h6.5v3.5M2.75 12h18.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
