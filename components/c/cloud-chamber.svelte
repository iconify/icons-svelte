<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jkvb0cb6h"/><path class="om9i5mdwy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cloud-chamber" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jkvb0cb6h) {
  d: path("M6.5 2.5h11A3.5 3.5 0 0 1 21 6v12a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 18V6a3.5 3.5 0 0 1 3.5-3.5");
}

:global(.om9i5mdwy) {
  d: path("M7.5 11.75h9a2.25 2.25 0 0 0 0-4.5a3.75 3.75 0 0 0-7 1a2 2 0 0 0-2 3.5m1 2.75v4m3.5-4V19m3.5-4.5v3");
}

</style>
