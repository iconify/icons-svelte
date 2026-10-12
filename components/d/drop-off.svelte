<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ywppwfrrh"/><path class="c1ofi6nid"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:drop-off" {...props}></Icon>
<style>
:global(.c1ofi6nid) {
  d: path("M4.25 16.25h15.5M12 2.75v8.5m-3.5-3.5l3.5 3.5l3.5-3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ywppwfrrh) {
  width: 15.5px;
  height: 7.5px;
  x: 4.25px;
  y: 13.75px;
  rx: 1.25px;
}

</style>
