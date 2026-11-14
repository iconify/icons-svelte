<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gbxsp6p4c"/><path class="nlp70zbiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:addendum" {...props}></Icon>
<style>
:global(.gbxsp6p4c) {
  d: path("M4.5 2.5h9l5 5V17h-14Zm2 14.5v4.5H13V17");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nlp70zbiv) {
  d: path("M13.5 2.5v5h5M8 10.5h7m-7 3.25h4.5");
}

</style>
