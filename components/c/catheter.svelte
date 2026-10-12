<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zn6mcva9u"/><rect class="eh339zb5j"/><rect class="vscgqh2sv"/><path class="kz52tkz-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:catheter" {...props}></Icon>
<style>
:global(.eh339zb5j) {
  width: 3.5px;
  height: 2.5px;
  x: 17.75px;
  y: 11px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kz52tkz-p) {
  d: path("M5.25 2.75a2 2.5 0 1 1 0 5a2 2.5 0 1 1 0-5");
}

:global(.vscgqh2sv) {
  width: 3.5px;
  height: 2.5px;
  x: 17.75px;
  y: 16.5px;
  rx: 1px;
}

:global(.zn6mcva9u) {
  d: path("M5.25 7.75V9.5C5.25 13 7.5 15 11 15h3c1.5 0 2-2.75 3.75-2.75M14 15c1.5 0 2 2.75 3.75 2.75");
}

</style>
