<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vrvtjpall"/><path class="mjmmdiava"/><path class="v22s1vbap"/><path class="k_916xngw"/><path class="x3gr8qf4w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chip-remove-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k_916xngw) {
  d: path("m14.5 10.5 3 3");
}

:global(.mjmmdiava) {
  d: path("M3 12a4 4 0 0 1 4 -4h10a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H7a4 4 0 0 1 -4 -4");
}

:global(.v22s1vbap) {
  d: path("M6.5 12H11");
}

:global(.vrvtjpall) {
  fill: currentColor;
  d: path("M3 12a4 4 0 0 1 4 -4h10a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H7a4 4 0 0 1 -4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x3gr8qf4w) {
  d: path("m17.5 10.5 -3 3");
}

</style>
