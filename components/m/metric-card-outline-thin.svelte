<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nnzlfsekh"/><path class="w28ybhbjm"/><path class="g85aieyzp"/><path class="e3dol68is"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:metric-card-outline-thin" {...props}></Icon>
<style>
:global(.e3dol68is) {
  d: path("M15 11v3");
}

:global(.g85aieyzp) {
  d: path("M11 9v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nnzlfsekh) {
  d: path("M2 8a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.w28ybhbjm) {
  d: path("M7 10v4");
}

</style>
