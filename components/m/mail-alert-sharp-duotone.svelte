<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="m_r9opbfg"/><path class="ngdah7b5i"/><path clip-rule="evenodd" class="l4wjw054o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mail-alert-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.l4wjw054o) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 20C20 20.552 19.552 21 19 21C18.448 21 18 20.552 18 20C18 19.448 18.448 19 19 19C19.552 19 20 19.448 20 20Z");
  stroke: none;
}

:global(.m_r9opbfg) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3H22C22.552 3 23 3.448 23 4V10C23 10.552 22.552 11 22 11H13V20C13 20.552 12.552 21 12 21H2C1.448 21 1 20.552 1 20V4C1 3.448 1.448 3 2 3Z");
  stroke: none;
}

:global(.ngdah7b5i) {
  d: path("M1.395 6.74L2 7L11.293 11C11.715 11.282 12.285 11.282 12.707 11L22 7L22.605 6.74M19 13V17");
}

</style>
