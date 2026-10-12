<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lmpo8pb2u"/><path class="mnfp72lnh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:oil-change" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lmpo8pb2u) {
  width: 18.5px;
  height: 4.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.mnfp72lnh) {
  d: path("M12 10c1.3 1.6 2 2.7 2 3.75a2 2 0 0 1-4 0c0-1.05.7-2.15 2-3.75m-9.25 8.5l1.5 2.75h15.5l1.5-2.75");
}

</style>
