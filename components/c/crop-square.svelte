<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ib3gs6bzn"/><path class="vu5ir404e"/><path class="jvf3gm4qy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:crop-square" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ib3gs6bzn) {
  d: path("M6 2.5V16a2 2 0 0 0 2 2h13.5");
}

:global(.jvf3gm4qy) {
  d: path("M10.75 9h2.5A1.75 1.75 0 0 1 15 10.75v2.5A1.75 1.75 0 0 1 13.25 15h-2.5A1.75 1.75 0 0 1 9 13.25v-2.5A1.75 1.75 0 0 1 10.75 9");
}

:global(.vu5ir404e) {
  d: path("M2.5 6H16a2 2 0 0 1 2 2v13.5");
}

</style>
