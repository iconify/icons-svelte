<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w9u-7prwp"/><rect class="lggdmi6jc"/><path class="qdwr1hbsf"/><circle class="z6cqk8a1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hand-truck" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lggdmi6jc) {
  width: 9.75px;
  height: 10px;
  x: 10px;
  y: 7.25px;
  rx: 1.25px;
}

:global(.qdwr1hbsf) {
  d: path("M14.75 7.25v3.25");
}

:global(.w9u-7prwp) {
  d: path("M3.25 3.5h2.5v13.75h15.5");
}

:global(.z6cqk8a1b) {
  cx: 8.5px;
  cy: 19px;
  r: 2.25px;
}

</style>
