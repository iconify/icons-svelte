<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="spx16kbxu"/><path class="ahz0mnbjh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:monitor-smartphone" {...props}></Icon>
<style>
:global(.ahz0mnbjh) {
  d: path("M17.125 9.5h1.75a2.625 2.625 0 0 1 2.625 2.625v6.75a2.625 2.625 0 0 1-2.625 2.625h-1.75a2.625 2.625 0 0 1-2.625-2.625v-6.75A2.625 2.625 0 0 1 17.125 9.5m-9.625 6v5m-3 0h6m6.75-1.75h1.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.spx16kbxu) {
  d: path("M11.5 15.5h-7a2 2 0 0 1-2-2v-8a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2v1");
}

</style>
