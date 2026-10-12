<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mbtk845mg"/><path class="jrq77bbus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cling-wrap" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jrq77bbus) {
  d: path("M5.5 8.75L6.8 7.5l1.3 1.25L9.4 7.5l1.3 1.25L12 7.5l1.3 1.25l1.3-1.25l1.3 1.25l1.3-1.25l1.3 1.25m-12.5 3h12q.75 0 .55.72l-2.1 7.56q-.2.72-.95.72h-12q-.75 0-.55-.72l2.1-7.56q.2-.72.95-.72");
}

:global(.mbtk845mg) {
  width: 18.5px;
  height: 7.5px;
  x: 2.75px;
  y: 4.25px;
  rx: 2px;
}

</style>
