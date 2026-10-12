<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="y82a5tbxn"/><rect class="jtf2kcb4d"/><rect class="c8zrbgb5n"/><path class="g82as4s4v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:infusion-pump" {...props}></Icon>
<style>
:global(.c8zrbgb5n) {
  width: 9px;
  height: 4.5px;
  x: 7.5px;
  y: 7.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

:global(.g82as4s4v) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 15.5h.01m3.24 0h.01m3.24 0h.01");
}

:global(.jtf2kcb4d) {
  width: 14.5px;
  height: 15.5px;
  x: 4.75px;
  y: 4.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.y82a5tbxn) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.75v2m0 15.5v1");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
