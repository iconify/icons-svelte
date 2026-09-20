<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b-fhdniix"/><path class="znv889pse"/><path class="x2nvzebcn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:outpaint-outline-thin" {...props}></Icon>
<style>
:global(.b-fhdniix) {
  d: path("M2 9a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x2nvzebcn) {
  d: path("M17 7h4v10h-4");
}

:global(.znv889pse) {
  d: path("m5 14 2.5 -2.5L10 14");
}

</style>
