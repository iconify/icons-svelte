<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aa-xam0us"/><path class="bv_xsgbxw"/><path class="im38brk4q"/><path class="jq33rvbor"/><path class="ma01ysb5t"/><path class="uxyzhxvwz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fasting-window-duotone-regular" {...props}></Icon>
<style>
:global(.aa-xam0us) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 7H3v10h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bv_xsgbxw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 7h3v10h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.im38brk4q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jq33rvbor) {
  d: path("M6 7H3v10h3");
}

:global(.ma01ysb5t) {
  d: path("M18 7h3v10h-3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uxyzhxvwz) {
  d: path("M7 12h10");
}

</style>
