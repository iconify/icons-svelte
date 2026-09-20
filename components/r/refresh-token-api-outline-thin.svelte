<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d8z1r1beo"/><path class="wzx0dxb2r"/><path class="rbp29tbnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:refresh-token-api-outline-thin" {...props}></Icon>
<style>
:global(.d8z1r1beo) {
  d: path("M15 5h3a3 3 0 0 1 3 3v9a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rbp29tbnz) {
  d: path("M9 12a1.5 1.5 0 0 1 1.5 -1.5h3A1.5 1.5 0 0 1 15 12a1.5 1.5 0 0 1 -1.5 1.5h-3A1.5 1.5 0 0 1 9 12");
}

:global(.wzx0dxb2r) {
  d: path("m12 2 3 3 -3 3");
}

</style>
