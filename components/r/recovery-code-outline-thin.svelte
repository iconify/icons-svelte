<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xfs8wlfhn"/><path class="ygr1bbcag"/><path class="mv2puevlj"/><path class="d6swx-tss"/><path class="bgtolgbkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recovery-code-outline-thin" {...props}></Icon>
<style>
:global(.bgtolgbkt) {
  d: path("M8 15.5h8");
}

:global(.d6swx-tss) {
  d: path("M14 12.5v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mv2puevlj) {
  d: path("M10 12.5v6");
}

:global(.xfs8wlfhn) {
  d: path("M5 11.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.ygr1bbcag) {
  d: path("M8 9.5a4 4 0 0 1 8 0");
}

</style>
