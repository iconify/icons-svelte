<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="q_xpl5b9t"/><path class="rcm8k73gn"/><path class="ywnhkcb3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hamburger-menu-linear" {...props}></Icon>
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

:global(.rcm8k73gn) {
  d: path("M20 12L4 12");
}

:global(.ywnhkcb3j) {
  d: path("M20 17L4 17");
}

</style>
