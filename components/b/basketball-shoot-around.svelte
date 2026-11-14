<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sao9cvb4o"/><path class="d0bgtwhch"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:basketball-shoot-around" {...props}></Icon>
<style>
:global(.d0bgtwhch) {
  d: path("M4 12q3.5 3.5 0 7m7-7q-3.5 3.5 0 7m2.5-12H21m0-4.5V12m-6.5-5l1.25 5.5h3L20 7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sao9cvb4o) {
  d: path("M2.5 15.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0m0 0h10");
}

</style>
