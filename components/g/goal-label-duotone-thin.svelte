<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="at1vv_brh"/><path class="hspeesv2z"/><path class="ujt25lh2u"/><path class="tv6hbrcra"/><path class="n6g909b9t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:goal-label-duotone-thin" {...props}></Icon>
<style>
:global(.at1vv_brh) {
  fill: currentColor;
  d: path("M9 6h3l3 3 -3 3H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hspeesv2z) {
  d: path("M5.5 3v5.5a6.5 6.5 0 0 0 13 0V3");
}

:global(.n6g909b9t) {
  d: path("M9 6h3l3 3 -3 3H9Z");
}

:global(.tv6hbrcra) {
  d: path("M8.5 20.5h7");
}

:global(.ujt25lh2u) {
  d: path("M12 15v5.5");
}

</style>
