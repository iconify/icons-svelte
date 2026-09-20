<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y4l98q7pn"/><path class="ifkuo0bhh"/><path class="rxwr8htky"/><path class="k74vnib1e"/><path class="ncbcfwbnb"/><path class="drlmmq_0c"/><path class="l3ca9u8kt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arbiter-duotone-regular" {...props}></Icon>
<style>
:global(.drlmmq_0c) {
  d: path("m10 7 5 5 -5 5");
}

:global(.ifkuo0bhh) {
  fill: currentColor;
  d: path("M3 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.k74vnib1e) {
  d: path("M3 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.l3ca9u8kt) {
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ncbcfwbnb) {
  d: path("M3 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rxwr8htky) {
  fill: currentColor;
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.y4l98q7pn) {
  fill: currentColor;
  d: path("M3 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
