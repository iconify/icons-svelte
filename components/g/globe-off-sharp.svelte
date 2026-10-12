<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="c3nfbpazq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:globe-off-sharp" {...props}></Icon>
<style>
:global(.c3nfbpazq) {
  d: path("M12 2.75C9.5 5.25 8.25 8.35 8.25 12S9.5 18.75 12 21.25c2.5-2.5 3.75-5.6 3.75-9.25S14.5 5.25 12 2.75ZM2.75 12h18.5");
}

:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
