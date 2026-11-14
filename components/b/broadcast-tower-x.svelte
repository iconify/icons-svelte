<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z4w_d6tcv"/><path class="ag5wthi6l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:broadcast-tower-x" {...props}></Icon>
<style>
:global(.ag5wthi6l) {
  d: path("m6.5 21.5l5.5-13l1.981 4.683M16 3.5a4.5 4.5 0 0 1 0 6m3-7a8 8 0 0 1 0 8m-11-7a4.5 4.5 0 0 0 0 6m-3-7a8 8 0 0 0 0 8m10.5 5l5 5m0-5l-5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z4w_d6tcv) {
  d: path("M10 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
