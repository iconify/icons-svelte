<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jf_a1l9lb"/><path class="ic3tlbtae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pie" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ic3tlbtae) {
  d: path("m3.25 15l17-4v4.25l-17 3.25Z");
}

:global(.jf_a1l9lb) {
  d: path("M3.25 15L14.5 6.75a2 2 0 0 1 3.25 1.15a2 2 0 0 1 2.5 3.1Z");
}

</style>
