<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hfpr3cbbr"/><path class="oiy9mib8b"/><path class="hhlxfkbol"/><path class="hxd6ts2yz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:reorder-broken" {...props}></Icon>
<style>
:global(.hfpr3cbbr) {
  d: path("M7 10H5M19 10L11 10");
}

:global(.hhlxfkbol) {
  d: path("M19 14L5 14");
}

:global(.hxd6ts2yz) {
  d: path("M19 6L5 6");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oiy9mib8b) {
  d: path("M17 18H19M5 18H13");
}

</style>
