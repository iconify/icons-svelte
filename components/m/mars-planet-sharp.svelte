<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hkmqn_bmj"/><circle class="pbit6lbsn"/><circle class="oruds0ork"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mars-planet-sharp" {...props}></Icon>
<style>
:global(.hkmqn_bmj) {
  d: path("M4.96 6h14.08A9.25 9.25 0 1 1 4.96 6Zm0 0h14.08A9.25 9.25 0 0 0 4.96 6Z");
}

:global(.oruds0ork) {
  cx: 15.25px;
  cy: 16px;
  r: 1.5px;
}

:global(.pbit6lbsn) {
  cx: 9px;
  cy: 12.5px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
