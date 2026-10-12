<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ayy_70qmh"/><path class="b74zm83sz"/><circle class="rh1oi0w6a"/><path class="k8y93bcan"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:punch-clock" {...props}></Icon>
<style>
:global(.ayy_70qmh) {
  width: 16.5px;
  height: 14px;
  x: 3.75px;
  y: 7.25px;
  rx: 2.5px;
}

:global(.b74zm83sz) {
  d: path("M9.5 7.25v-3.5a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v3.5Zm-2 2.25h9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k8y93bcan) {
  d: path("M12 13.75v1.5l1.25 1");
}

:global(.rh1oi0w6a) {
  cx: 12px;
  cy: 15.25px;
  r: 3.25px;
}

</style>
