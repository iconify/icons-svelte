<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a5bpmnbry"/><path class="wyli5loxo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:datacenter-building" {...props}></Icon>
<style>
:global(.a5bpmnbry) {
  d: path("M2.5 21.5h19M5 21.5v-18h14v18M8 7.5h8m-8 4h8m-8 4h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wyli5loxo) {
  d: path("M10.5 21.5v-3h3v3");
}

</style>
