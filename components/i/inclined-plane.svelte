<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zykafu85r"/><path class="jwgoos61n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:inclined-plane" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jwgoos61n) {
  d: path("m9.84 12.69l2.5 1.66q.63.41 1.04-.22l1.66-2.49q.41-.63-.22-1.04l-2.5-1.66q-.63-.41-1.04.22l-1.66 2.49q-.41.63.22 1.04m6.66 7.56a4.75 4.75 0 0 1 .79-2.62");
}

:global(.zykafu85r) {
  d: path("M3.75 20.25h16.5q1 0 .17-.55L3.58 8.55Q2.75 8 2.75 9v10.25q0 1 1 1");
}

</style>
