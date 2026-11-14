<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tgrrbqyab"/><path class="ip9_wgbok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:leaf-hand" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ip9_wgbok) {
  d: path("m12.75 16.25l5.25-2.5a1.5 1.5 0 0 1 1.75 2.5l-6 4.25H2.5");
}

:global(.tgrrbqyab) {
  d: path("M9.5 10.5c0-5 2.25-7 7-7c0 5-2.25 7-7 7m-7 4h3l3.25-1.25h3.75a1.5 1.5 0 0 1 0 3H9.75");
}

</style>
