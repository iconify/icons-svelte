<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c7dgfu7wx"/><path class="lgyhdeb-s"/><path class="j1kezkxcy"/><path class="ezp0d4btt"/><path class="gnit4mb6c"/><path class="lkpe2ldcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recursive-split-outline-thin" {...props}></Icon>
<style>
:global(.c7dgfu7wx) {
  d: path("M2 4h20");
}

:global(.ezp0d4btt) {
  d: path("M2 16h3");
}

:global(.gnit4mb6c) {
  d: path("M7.5 16h3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j1kezkxcy) {
  d: path("M13.5 10H22");
}

:global(.lgyhdeb-s) {
  d: path("M2 10h8.5");
}

:global(.lkpe2ldcq) {
  d: path("M13.5 16H22");
}

</style>
