<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kamdbib6v"/><path class="v-q4myyjv"/><path class="n2ya_p02p"/><path class="h5yksf4iw"/><path class="e3fkgnlsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-desk-outline-thin" {...props}></Icon>
<style>
:global(.e3fkgnlsf) {
  d: path("M13 16h7");
}

:global(.h5yksf4iw) {
  d: path("M13 12h7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kamdbib6v) {
  d: path("M2 7h20");
}

:global(.n2ya_p02p) {
  d: path("M13 7v13h7V7");
}

:global(.v-q4myyjv) {
  d: path("M4 7v13");
}

</style>
