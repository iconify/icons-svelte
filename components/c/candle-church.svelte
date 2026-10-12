<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bs99rab-u"/><rect class="uy9sd2abu"/><path class="idf8m8x4y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:candle-church" {...props}></Icon>
<style>
:global(.bs99rab-u) {
  d: path("M12 2.75C13.25 4 14 5 14 6a2 2 0 0 1-4 0c0-1 .75-2 2-3.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.idf8m8x4y) {
  d: path("M12 13.75v5m-2-3h4");
}

:global(.uy9sd2abu) {
  width: 8.5px;
  height: 10.25px;
  x: 7.75px;
  y: 11px;
  rx: 1.5px;
}

</style>
