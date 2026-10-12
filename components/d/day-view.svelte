<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="luxaszu4f"/><path class="nmh0dk4nr"/><rect class="dv1k1hbdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:day-view" {...props}></Icon>
<style>
:global(.dv1k1hbdm) {
  width: 6.5px;
  height: 4.75px;
  x: 11.25px;
  y: 11.25px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.luxaszu4f) {
  width: 17.5px;
  height: 17.5px;
  x: 3.25px;
  y: 3.25px;
  rx: 2.5px;
}

:global(.nmh0dk4nr) {
  d: path("M3.25 8.25h17.5M6 12h2m-2 3h2m-2 3h2");
}

</style>
