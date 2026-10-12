<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vijr9ibmd"/><path class="xd-vp3ztb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:inventory-count" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vijr9ibmd) {
  width: 15.5px;
  height: 17.5px;
  x: 4.25px;
  y: 3.75px;
  rx: 1.5px;
}

:global(.xd-vp3ztb) {
  d: path("M9 3.75v3h6v-3M9 10v7.5m3-7.5v7.5m3-7.5v7.5m-8-1.75l10-4.5");
}

</style>
