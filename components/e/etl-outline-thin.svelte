<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lemjmdn8v"/><path class="v8xooabzi"/><path class="ptj3znbqu"/><path class="cf8eb9bym"/><path class="x909-s8qx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:etl-outline-thin" {...props}></Icon>
<style>
:global(.cf8eb9bym) {
  d: path("M18.5 12H22");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lemjmdn8v) {
  d: path("M2 12h4.5");
}

:global(.ptj3znbqu) {
  d: path("M9 9a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

:global(.v8xooabzi) {
  d: path("m4.5 10 2 2 -2 2");
}

:global(.x909-s8qx) {
  d: path("m20 10 2 2 -2 2");
}

</style>
