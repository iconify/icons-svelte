<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="c2yjeabor"/><path class="kwpresbvr"/><path class="uxk8nvd9q"/><path class="ukks7tb_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:air-fryer" {...props}></Icon>
<style>
:global(.c2yjeabor) {
  width: 13.75px;
  height: 18.5px;
  x: 3.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

:global(.kwpresbvr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 10.75H17");
}

:global(.ukks7tb_f) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 13.25h2.5a1.25 1.25 0 0 1 1.25 1.25v5");
}

:global(.uxk8nvd9q) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.125 6.75h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
