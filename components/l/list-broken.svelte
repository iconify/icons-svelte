<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="q_xpl5b9t"/><path class="eyprd0b7p"/><path class="uv1duwbne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-broken" {...props}></Icon>
<style>
:global(.eyprd0b7p) {
  d: path("M15 12L4 12");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q_xpl5b9t) {
  d: path("M20 7L4 7");
}

:global(.uv1duwbne) {
  d: path("M9 17H4");
}

</style>
