<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0wnaopfd"/><circle class="n81udiknj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:reminder-bell" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n81udiknj) {
  cx: 19px;
  cy: 4.5px;
  r: 1.5px;
}

:global(.r0wnaopfd) {
  d: path("M10.5 4.5a5 5 0 0 0-5 5v3.25l-1.5 3h13l-1.5-3V9.5a5 5 0 0 0-5-5m-2 14.25a2 2 0 0 0 4 0");
}

</style>
