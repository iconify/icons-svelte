<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w6-sjebpg"/><path class="pouzf7kdk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:language" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pouzf7kdk) {
  d: path("M19.25 5c-.5 3.5-2.25 5.75-6 7");
}

:global(.w6-sjebpg) {
  d: path("m3 21l4-10l4 10m-6.5-3.5h5M13 5h8m-4-2.25V5m-2.25 0c.5 3.5 2.25 5.75 6 7");
}

</style>
