<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xne2_4juu"/><path class="sdyasqrsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:farm-robot" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sdyasqrsz) {
  d: path("M4 19.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m6 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8.5 2V15q0-4.5 3-4.5c0 2.5-1 4.5-3 4.5m-12-3h.01m3.99 0h.01");
}

:global(.xne2_4juu) {
  d: path("M6.5 7h4a3.5 3.5 0 0 1 3.5 3.5v4a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 3 14.5v-4A3.5 3.5 0 0 1 6.5 7m2 0V5.5M7 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
