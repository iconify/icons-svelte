<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="dlbbvlb-m"/><path class="j3ukzrb5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:image-wrap-right-sharp-fill" {...props}></Icon>
<style>
:global(.dlbbvlb-m) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 6L21 6C21.5523 6 22 6.4477 22 7L22 17C22 17.5523 21.5523 18 21 18L11 18C10.4477 18 10 17.5523 10 17L10 7C10 6.4477 10.4477 6 11 6Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.j3ukzrb5m) {
  d: path("M2 3L22 3M2 21L22 21M2 9L8 9M2 15L8 15");
}

</style>
