<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="elj7lmb0r"/><path class="c9x1hpblo"/><circle class="aemasgwuc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:nursing-mother-sharp" {...props}></Icon>
<style>
:global(.aemasgwuc) {
  cx: 14px;
  cy: 11.5px;
  r: 2px;
}

:global(.c9x1hpblo) {
  d: path("M5 21v-9.5h4a5 5 0 0 0 10 0");
}

:global(.elj7lmb0r) {
  cx: 9.5px;
  cy: 5.5px;
  r: 2.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
