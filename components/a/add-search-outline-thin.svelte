<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p367mshbv"/><path class="rseiusb3q"/><path class="mvkhxckkt"/><path class="jlfjgzbqx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:add-search-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jlfjgzbqx) {
  d: path("M9 9h6");
}

:global(.mvkhxckkt) {
  d: path("M12 6v6");
}

:global(.p367mshbv) {
  d: path("M5.5 10a6.5 6.5 0 1 0 13 0 6.5 6.5 0 1 0 -13 0");
}

:global(.rseiusb3q) {
  d: path("M16.5 14.5 21 19");
}

</style>
