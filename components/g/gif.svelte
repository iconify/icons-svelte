<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="h5_ol53lx"/><path class="d472zr3hm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gif" {...props}></Icon>
<style>
:global(.d472zr3hm) {
  d: path("M9.27 10.23A2.5 2.5 0 1 0 10 12H8.25m4.5-2.5v5m2.75 0v-5h3m-3 2.5h2.25");
}

:global(.h5_ol53lx) {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  rx: 3px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
