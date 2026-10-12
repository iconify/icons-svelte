<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w677y9sfz"/><path class="ds7rev47f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:grayscale" {...props}></Icon>
<style>
:global(.ds7rev47f) {
  d: path("M15.25 3.34a9.25 9.25 0 0 1 0 17.32ZM9 10.5l4.25-4.25M9 15l4.25-4.25M9.5 19l3.75-3.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w677y9sfz) {
  d: path("M12 2.75a9.25 9.25 0 1 0 0 18.5a9.25 9.25 0 1 0 0-18.5");
}

</style>
