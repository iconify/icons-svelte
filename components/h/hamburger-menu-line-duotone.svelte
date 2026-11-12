<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="q_xpl5b9t"/><path class="t6qtu5t7v"/><path class="ywnhkcb3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hamburger-menu-line-duotone" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q_xpl5b9t) {
  d: path("M20 7L4 7");
}

:global(.t6qtu5t7v) {
  d: path("M20 12L4 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ywnhkcb3j) {
  d: path("M20 17L4 17");
}

</style>
