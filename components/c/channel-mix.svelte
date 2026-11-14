<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qv_eo_bbg"/><path class="z-soe-bar"/><path class="iu8vmabud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:channel-mix" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iu8vmabud) {
  d: path("M9.75 14.25a5.75 5.75 0 1 0 11.5 0a5.75 5.75 0 1 0-11.5 0");
}

:global(.qv_eo_bbg) {
  d: path("M6.25 8.25a5.75 5.75 0 1 0 11.5 0a5.75 5.75 0 1 0-11.5 0");
}

:global(.z-soe-bar) {
  d: path("M2.75 14.25a5.75 5.75 0 1 0 11.5 0a5.75 5.75 0 1 0-11.5 0");
}

</style>
