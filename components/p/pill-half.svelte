<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nkxwd0hwh"/><path class="jbgj_xbos"/><path class="yo4ia5pve"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pill-half" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jbgj_xbos) {
  d: path("M2.75 10v3.5a7.75 4 0 0 0 7.75 4V14m3-8a7.75 4 0 0 1 0 8Z");
}

:global(.nkxwd0hwh) {
  d: path("M10.5 6a7.75 4 0 0 0 0 8Z");
}

:global(.yo4ia5pve) {
  d: path("M21.25 10v3.5a7.75 4 0 0 1-7.75 4V14");
}

</style>
