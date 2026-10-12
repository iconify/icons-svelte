<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="f-qbcacln"/><path class="pb0oqlbgj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:overpass" {...props}></Icon>
<style>
:global(.f-qbcacln) {
  width: 7.5px;
  height: 18.5px;
  x: 8.25px;
  y: 2.75px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pb0oqlbgj) {
  d: path("M12 5.25v2.5m0 3v2.5m0 3v2.5m-9.25-10H6.5m11 0h3.75m-18.5 6.5H6.5m11 0h3.75");
}

</style>
