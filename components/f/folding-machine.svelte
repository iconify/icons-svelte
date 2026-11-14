<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vsplp4bht"/><path class="ru3tnrb6h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:folding-machine" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ru3tnrb6h) {
  d: path("M13 21.5v-3h3");
}

:global(.vsplp4bht) {
  d: path("M6 6.5h12a3.5 3.5 0 0 1 3.5 3.5v1.5A3.5 3.5 0 0 1 18 15H6a3.5 3.5 0 0 1-3.5-3.5V10A3.5 3.5 0 0 1 6 6.5m2 0v-4h8v4M8 15v6.5h5l3-3V15");
}

</style>
