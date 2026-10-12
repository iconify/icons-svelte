<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rmm1voz9v"/><path class="le1v6bbgz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:e-ticket" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.le1v6bbgz) {
  d: path("M10.75 5.5h2.5m-2.75 13h3m-5-9.25a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v1.5a1.25 1.25 0 0 0 0 2.5v1.5a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1v-1.5a1.25 1.25 0 0 0 0-2.5Z");
}

:global(.rmm1voz9v) {
  width: 12.5px;
  height: 18.5px;
  x: 5.75px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
