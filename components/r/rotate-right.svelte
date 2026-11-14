<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6wn4v-tc"/><path class="lvnpwkv_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rotate-right" {...props}></Icon>
<style>
:global(.g6wn4v-tc) {
  d: path("M3.5 20A13.5 13.5 0 0 1 17 6.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lvnpwkv_c) {
  d: path("M13.5 3L17 6.5L13.5 10");
}

</style>
