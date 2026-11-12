<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="doy9q4b5f"/><path class="c5yb8bdcb"/><path class="pr1jznbmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:danger-circle-line-duotone" {...props}></Icon>
<style>
:global(.c5yb8bdcb) {
  d: path("M12 7V13");
}

:global(.doy9q4b5f) {
  cx: 12px;
  cy: 12px;
  r: 10px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pr1jznbmm) {
  stroke-linejoin: round;
  d: path("M12 16H12.0001");
}

</style>
