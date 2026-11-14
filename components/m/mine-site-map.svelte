<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hojrysjhs"/><path class="ugxjdebin"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mine-site-map" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hojrysjhs) {
  d: path("m3.977 4.767l7.75-1.224a1.8 1.8 0 0 1 .546 0l7.75 1.224A1.75 1.75 0 0 1 21.5 6.495v11.957a1.75 1.75 0 0 1-2.023 1.729l-7.204-1.138a1.8 1.8 0 0 0-.546 0l-7.204 1.138A1.75 1.75 0 0 1 2.5 18.452V6.495a1.75 1.75 0 0 1 1.477-1.728M12 3.5V19m-9.5-5.75h19M7 4.5v15.25");
}

:global(.ugxjdebin) {
  fill: currentColor;
  d: path("m15.83 8.959l.045-.084a.994.994 0 0 1 1.75 0l.045.084a1.045 1.045 0 0 1-.92 1.541a1.045 1.045 0 0 1-.92-1.541");
}

</style>
