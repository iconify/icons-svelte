<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x00qgzx7x"/><rect class="ejosx0b0b"/><path class="ge-6c_bbk"/><rect class="nkn537bap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:nda-document" {...props}></Icon>
<style>
:global(.ejosx0b0b) {
  width: 8.5px;
  height: 2.5px;
  x: 7.75px;
  y: 5.5px;
  rx: 1px;
}

:global(.ge-6c_bbk) {
  d: path("M7.75 11h8.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nkn537bap) {
  width: 5.5px;
  height: 2.5px;
  x: 7.75px;
  y: 14px;
  rx: 1px;
}

:global(.x00qgzx7x) {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
