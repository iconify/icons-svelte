<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e1y9aqblm"/><path class="i0bv9be2e"/><path class="pop59pb2d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:repeat-one-minimalistic-broken" {...props}></Icon>
<style>
:global(.e1y9aqblm) {
  d: path("M16 12L8 12");
}

:global(.i0bv9be2e) {
  stroke-linejoin: round;
  d: path("M9.5 19H9.00028C6.62153 19 4.51981 17.8135 3.25478 16M9 3L11 5H9C5.13401 5 2 8.13401 2 12");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pop59pb2d) {
  stroke-linejoin: round;
  d: path("M15 21L13 19H15C18.866 19 22 15.866 22 12M14.5 5H15C17.3787 5 19.4804 6.18652 20.7453 8");
}

</style>
