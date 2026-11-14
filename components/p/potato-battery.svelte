<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n6vxtabal"/><path class="vthzcsugq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:potato-battery" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n6vxtabal) {
  d: path("M2.5 15.5a9.5 6 0 1 0 19 0a9.5 6 0 1 0-19 0m5.5-3V4");
}

:global(.vthzcsugq) {
  d: path("M15.5 12.5v-5c0-3.5 3.5-4 5-1.5M6 15.5h.01M15.5 18h.01");
}

</style>
