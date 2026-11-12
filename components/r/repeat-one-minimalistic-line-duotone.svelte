<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j-9qosbks"/><path class="ygwi57j2x"/><path class="e1y9aqblm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:repeat-one-minimalistic-line-duotone" {...props}></Icon>
<style>
:global(.e1y9aqblm) {
  d: path("M16 12L8 12");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j-9qosbks) {
  stroke-linejoin: round;
  d: path("M9.5 19H9.00028C5.13428 19 2 15.866 2 12C2 8.13401 5.13401 5 9 5H11L9 3");
}

:global(.ygwi57j2x) {
  stroke-linejoin: round;
  d: path("M15 21L13 19H15C18.866 19 22 15.866 22 12C22 8.13401 18.866 5 15 5H14.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
