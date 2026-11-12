<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p9h4jybmo"/><path class="fdi87hbgw"/><path class="urwe8bb9z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:close-broken" {...props}></Icon>
<style>
:global(.fdi87hbgw) {
  d: path("M12.0068 12L5.00684 19");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p9h4jybmo) {
  d: path("M19.0068 5L15.5068 8.5");
}

:global(.urwe8bb9z) {
  d: path("M19 19L5 5");
}

</style>
