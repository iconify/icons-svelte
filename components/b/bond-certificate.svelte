<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="j79tbyzzd"/><path class="zzn37kb-q"/><circle class="io--5q1sp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bond-certificate" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.io--5q1sp) {
  cx: 15.5px;
  cy: 12.75px;
  r: 2.75px;
}

:global(.j79tbyzzd) {
  width: 18.5px;
  height: 14.75px;
  x: 2.75px;
  y: 3.25px;
  rx: 2.5px;
}

:global(.zzn37kb-q) {
  d: path("M6.25 7.25h11.5m-11.5 3.5H10m4 4.3v6.2l1.5-1l1.5 1v-6.2");
}

</style>
