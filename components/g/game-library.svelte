<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w0891t8_y"/><path class="t0cw1v7ql"/><rect class="tgree443r"/><path class="hs9xvsb6k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:game-library" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hs9xvsb6k) {
  d: path("M5.75 7.75v13.5");
}

:global(.t0cw1v7ql) {
  d: path("M5.25 7.75v-.5a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v9.5a2 2 0 0 1-2 2h-.5");
}

:global(.tgree443r) {
  width: 13px;
  height: 13.5px;
  x: 2.75px;
  y: 7.75px;
  rx: 2px;
}

:global(.w0891t8_y) {
  d: path("M7.75 5.25v-.5a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v9.5a2 2 0 0 1-2 2h-.5");
}

</style>
