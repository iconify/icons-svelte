<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="d84qmtbgz"/><path class="mijbvibik"/><rect class="hr74dlbru"/><path class="mjcmzysvq"/><rect class="s0l58-izb"/><path class="mz348jb2q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:container-stack" {...props}></Icon>
<style>
:global(.d84qmtbgz) {
  width: 8px;
  height: 7px;
  x: 2.75px;
  y: 14.25px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hr74dlbru) {
  width: 8px;
  height: 7px;
  x: 13.25px;
  y: 14.25px;
  rx: 1px;
}

:global(.mijbvibik) {
  d: path("M5.5 16.75v2m2.5-2v2");
}

:global(.mjcmzysvq) {
  d: path("M16 16.75v2m2.5-2v2");
}

:global(.mz348jb2q) {
  d: path("M10.5 6.75v2.5m3-2.5v2.5");
}

:global(.s0l58-izb) {
  width: 9px;
  height: 7.5px;
  x: 7.5px;
  y: 4.25px;
  rx: 1px;
}

</style>
