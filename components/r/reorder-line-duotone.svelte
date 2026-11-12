<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ncsx83b9b"/><path class="opf63ccaz"/><path class="h_-kaybie"/><path class="b-fd45bwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:reorder-line-duotone" {...props}></Icon>
<style>
:global(.b-fd45bwd) {
  d: path("M19 18L5 18");
}

:global(.h_-kaybie) {
  d: path("M19 6L5 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ncsx83b9b) {
  d: path("M19 10L5 10");
}

:global(.opf63ccaz) {
  d: path("M19 14L5 14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
