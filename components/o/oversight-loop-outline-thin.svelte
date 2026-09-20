<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d8z1r1beo"/><path class="wzx0dxb2r"/><path class="bu2gtz1yi"/><path class="l7lvdwbxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:oversight-loop-outline-thin" {...props}></Icon>
<style>
:global(.bu2gtz1yi) {
  d: path("M8.24 11.63a4 4 0 0 1 7.5 0");
}

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

:global(.l7lvdwbxu) {
  d: path("M10 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.wzx0dxb2r) {
  d: path("m12 2 3 3 -3 3");
}

</style>
