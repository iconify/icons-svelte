<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u856clbvr"/><path class="w7d0inb0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hologram" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u856clbvr) {
  d: path("M7.125 3h9.75A2.625 2.625 0 0 1 19.5 5.625v4.75A2.625 2.625 0 0 1 16.875 13h-9.75A2.625 2.625 0 0 1 4.5 10.375v-4.75A2.625 2.625 0 0 1 7.125 3M4.5 19.5a7.5 2 0 1 0 15 0a7.5 2 0 1 0-15 0");
}

:global(.w7d0inb0b) {
  d: path("m8 10l3-3.25L13.5 9L16 6.5");
}

</style>
