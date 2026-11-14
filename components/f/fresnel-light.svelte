<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="czu33icqx"/><path class="dlr51bc6m"/><path class="fhim5_b7s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fresnel-light" {...props}></Icon>
<style>
:global(.czu33icqx) {
  d: path("M4.5 10a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

:global(.dlr51bc6m) {
  d: path("M7.25 10a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0");
}

:global(.fhim5_b7s) {
  d: path("M10 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 7.5v4m-4 0h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
