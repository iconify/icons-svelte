<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qr_6dff5e"/><path class="ayar2fnkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hand-crossed-fingers" {...props}></Icon>
<style>
:global(.ayar2fnkf) {
  d: path("M9 16.5h6m-.5-3.5l-5-8m0 8l5-8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qr_6dff5e) {
  width: 12px;
  height: 7px;
  x: 6px;
  y: 13px;
  rx: 3px;
}

</style>
