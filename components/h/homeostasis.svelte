<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eret2jbmb"/><path class="yym_uyaih"/><path class="z4a9ptbec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:homeostasis" {...props}></Icon>
<style>
:global(.eret2jbmb) {
  d: path("M14.736 4.482a8 8 0 0 1 0 15.036");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yym_uyaih) {
  d: path("m16 16.75l-1.25 2.75l2.75 1.25m-8.236-1.232a8 8 0 0 1 0-15.036");
}

:global(.z4a9ptbec) {
  d: path("m8 16.75l1.25 2.75l-2.75 1.25M8 12h8");
}

</style>
