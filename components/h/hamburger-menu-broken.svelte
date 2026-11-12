<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c_wyezbbg"/><path class="ihwi1gbya"/><path class="zj3_xl2hb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hamburger-menu-broken" {...props}></Icon>
<style>
:global(.c_wyezbbg) {
  d: path("M4 7L7 7M11 7L20 7");
}

:global(.ihwi1gbya) {
  d: path("M20 17H17M13 17L4 17");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zj3_xl2hb) {
  d: path("M4 12H7L20 12");
}

</style>
