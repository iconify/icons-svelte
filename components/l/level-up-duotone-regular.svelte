<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="haqmubngg"/><path class="mh_3yqm3z"/><path class="wqwx994ue"/><path class="on_ehobtw"/><path class="jhi1s7bxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:level-up-duotone-regular" {...props}></Icon>
<style>
:global(.haqmubngg) {
  fill: currentColor;
  d: path("M3 10h18v10H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jhi1s7bxb) {
  d: path("m15 5 3 -3 3 3");
}

:global(.mh_3yqm3z) {
  d: path("M3 10h18v10H3Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.on_ehobtw) {
  d: path("M18 7V2");
}

:global(.wqwx994ue) {
  d: path("M14 10v10");
}

</style>
