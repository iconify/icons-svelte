<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c_t5ec7az"/><path class="wdrs_ubhq"/><path class="pa_ryubtq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:location-precise" {...props}></Icon>
<style>
:global(.c_t5ec7az) {
  d: path("M12 21.5c-4-4.5-7-8-7-12a7 7 0 0 1 14 0c0 4-3 7.5-7 12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pa_ryubtq) {
  fill: currentColor;
  d: path("M11 9.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

:global(.wdrs_ubhq) {
  d: path("M8.25 9.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

</style>
