<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="foekz_rii"/><path class="z7dtlqbvr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:map-layer-poi" {...props}></Icon>
<style>
:global(.foekz_rii) {
  d: path("M12 21.5c-3-2.75-7.5-7-7.5-11.5a7.5 7.5 0 0 1 15 0c0 4.5-4.5 8.75-7.5 11.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z7dtlqbvr) {
  d: path("M9.25 10a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

</style>
