<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gbateub4h"/><path class="mewl0mb5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:astronaut-salute" {...props}></Icon>
<style>
:global(.gbateub4h) {
  d: path("M7.75 5.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m2.25 6h2a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3a3 3 0 0 1 3-3m-1 6v4m4-4v4M7 14l-2.5 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mewl0mb5m) {
  d: path("m15 14l3.5-3.5L14.25 5");
}

</style>
