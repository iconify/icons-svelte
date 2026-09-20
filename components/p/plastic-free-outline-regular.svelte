<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c2k5-kblh"/><path class="d45kg_ien"/><path class="y29zmn0-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:plastic-free-outline-regular" {...props}></Icon>
<style>
:global(.c2k5-kblh) {
  d: path("M9 8v12h6V8Z");
}

:global(.d45kg_ien) {
  d: path("M10.5 8V4h3v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y29zmn0-m) {
  d: path("M5 20 19 6");
}

</style>
