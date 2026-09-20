<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="chwfr3btt"/><path class="uw59zbbfm"/><path class="t-tlxbnvp"/><path class="sk9ov1b7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-resource-list-duotone-regular" {...props}></Icon>
<style>
:global(.chwfr3btt) {
  fill: currentColor;
  d: path("M13 2h-3L7 5v12h10V7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sk9ov1b7d) {
  d: path("M16 7h-3l-3 3v12h10V12");
}

:global(.t-tlxbnvp) {
  d: path("M13 2h-3L7 5v12h10V7");
}

:global(.uw59zbbfm) {
  fill: currentColor;
  d: path("M16 7h-3l-3 3v12h10V12");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
