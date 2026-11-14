<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mv_gf-56q"/><path class="glbov0buj"/><path class="y3honzxlq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:quote-open" {...props}></Icon>
<style>
:global(.glbov0buj) {
  d: path("M3.75 15.5c0-4.5 2-7.5 5.75-9m4.25 9a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mv_gf-56q) {
  d: path("M3.75 15.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

:global(.y3honzxlq) {
  d: path("M13.75 15.5c0-4.5 2-7.5 5.75-9");
}

</style>
