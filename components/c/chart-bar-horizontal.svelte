<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ds8we6g8d"/><rect class="tx0543giw"/><rect class="mcgjkfzkj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chart-bar-horizontal" {...props}></Icon>
<style>
:global(.ds8we6g8d) {
  width: 9px;
  height: 3.25px;
  x: 3.75px;
  y: 4.5px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mcgjkfzkj) {
  width: 12px;
  height: 3.25px;
  x: 3.75px;
  y: 16px;
  rx: 1px;
}

:global(.tx0543giw) {
  width: 16.5px;
  height: 3.25px;
  x: 3.75px;
  y: 10.25px;
  rx: 1px;
}

</style>
