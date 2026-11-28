<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xujddvbqo"/><path class="ickvo7b_n"/><path clip-rule="evenodd" class="u2zjuxbiz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circuit-board-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ickvo7b_n) {
  d: path("M18 7H23M18 12H23M18 17H23M5 18H11M2 2H18V22H2V2ZM6 6H14V13H6V6Z");
}

:global(.u2zjuxbiz) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 18C15 18.552 14.552 19 14 19C13.448 19 13 18.552 13 18C13 17.448 13.448 17 14 17C14.552 17 15 17.448 15 18Z");
  stroke: none;
}

:global(.xujddvbqo) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 12V22C19 22.552 18.552 23 18 23H2C1.448 23 1 22.552 1 22V2C1 1.448 1.448 1 2 1H18C18.552 1 19 1.448 19 2V12Z");
  stroke: none;
}

</style>
