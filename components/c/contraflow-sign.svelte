<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ceozypbtr"/><path class="wwjs67byu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:contraflow-sign" {...props}></Icon>
<style>
:global(.ceozypbtr) {
  d: path("m14.295 6.63l5.538 9.97a2.625 2.625 0 0 1-2.294 3.9H6.461a2.625 2.625 0 0 1-2.294-3.9l5.538-9.97a2.625 2.625 0 0 1 4.59 0M9.75 12.5v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wwjs67byu) {
  d: path("m8.75 16.5l1 1l1-1m3-4v5m-1-4l1-1l1 1");
}

</style>
