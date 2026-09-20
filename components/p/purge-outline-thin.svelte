<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tcztq2-_v"/><path class="mg7aqnbsf"/><path class="i1jp0gbac"/><path class="emoyz4b2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:purge-outline-thin" {...props}></Icon>
<style>
:global(.emoyz4b2o) {
  d: path("m15 11 -6 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i1jp0gbac) {
  d: path("m9 11 6 6");
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.tcztq2-_v) {
  d: path("M5 9a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

</style>
