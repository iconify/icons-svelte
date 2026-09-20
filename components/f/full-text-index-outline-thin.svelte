<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6fi9qmtq"/><path class="mlhk78k2d"/><path class="wh4xgnrmo"/><path class="m-3gekbbg"/><path class="l-37rlmum"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:full-text-index-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k6fi9qmtq) {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.l-37rlmum) {
  d: path("m17 18 3 3");
}

:global(.m-3gekbbg) {
  d: path("M12 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.mlhk78k2d) {
  d: path("M5 8h14");
}

:global(.wh4xgnrmo) {
  d: path("M5 12h10");
}

</style>
