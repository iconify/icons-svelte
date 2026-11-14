<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z6dogkb0p"/><path class="yq93jtbsv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:part-time-job" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yq93jtbsv) {
  d: path("M12 12V6.25A5.75 5.75 0 0 1 17.75 12Zm0-3.5l3.5 3.5");
}

:global(.z6dogkb0p) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M12 2.5v1.75M21.5 12h-1.75M12 21.5v-1.75M2.5 12h1.75");
}

</style>
