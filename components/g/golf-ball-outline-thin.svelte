<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g58rs14ba"/><path class="x67_elb1a"/><path class="wj95cacbv"/><path class="p-3tqnbzb"/><path class="yegul17ht"/><path class="xslfg2evh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:golf-ball-outline-thin" {...props}></Icon>
<style>
:global(.g58rs14ba) {
  d: path("M4 11a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p-3tqnbzb) {
  d: path("M9 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.wj95cacbv) {
  d: path("M13 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.x67_elb1a) {
  d: path("M8 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.xslfg2evh) {
  d: path("M6 21h12");
}

:global(.yegul17ht) {
  d: path("M14 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
