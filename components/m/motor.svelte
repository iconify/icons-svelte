<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="asfmwib5x"/><path class="d-zgbzbgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:motor" {...props}></Icon>
<style>
:global(.asfmwib5x) {
  width: 12.5px;
  height: 11.5px;
  x: 3.75px;
  y: 6.25px;
  rx: 2.5px;
}

:global(.d-zgbzbgn) {
  d: path("m10.5 8.75l-2 3.5h3l-2 3.5M16.25 12h5m-14.5 5.75v2.5m6.5-2.5v2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
