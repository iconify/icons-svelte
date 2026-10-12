<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xv36-fbyj"/><rect class="qmr2itqcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:reverse-logistics" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qmr2itqcq) {
  width: 6px;
  height: 6px;
  x: 9px;
  y: 9px;
  rx: 0.75px;
}

:global(.xv36-fbyj) {
  d: path("M4.75 10a7.5 7.5 0 0 1 13.5-3.6m1 7.6a7.5 7.5 0 0 1-13.5 3.6M18.5 2.75V6.5h-3.75M5.5 21.25V17.5h3.75");
}

</style>
