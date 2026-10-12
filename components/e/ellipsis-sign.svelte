<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="kx10lybnk"/><circle class="nm_s7seyo"/><circle class="ags78j8uq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ellipsis-sign" {...props}></Icon>
<style>
:global(.ags78j8uq) {
  cx: 19px;
  cy: 17.5px;
  r: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kx10lybnk) {
  cx: 5px;
  cy: 17.5px;
  r: 1.75px;
}

:global(.nm_s7seyo) {
  cx: 12px;
  cy: 17.5px;
  r: 1.75px;
}

</style>
