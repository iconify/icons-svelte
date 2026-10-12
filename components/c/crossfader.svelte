<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r9d2zvz9i"/><rect class="z4feijbvk"/><path class="ul4v2mbki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:crossfader" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r9d2zvz9i) {
  d: path("M2.75 12H6.5m9 0h5.75M5.5 5.5V8m13-2.5V8m-13 8v2.5m13-2.5v2.5");
}

:global(.ul4v2mbki) {
  d: path("M11 10v4");
}

:global(.z4feijbvk) {
  width: 5.5px;
  height: 8.5px;
  x: 8.25px;
  y: 7.75px;
  rx: 1.5px;
}

</style>
