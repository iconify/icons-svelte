<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aqwtj_auq"/><path class="g5x-39ykz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:image-inline-duotone" {...props}></Icon>
<style>
:global(.aqwtj_auq) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 8L14 8C15.1046 8 16 8.8954 16 10L16 14C16 15.1046 15.1046 16 14 16L10 16C8.8954 16 8 15.1046 8 14L8 10C8 8.8954 8.8954 8 10 8Z");
  stroke: none;
}

:global(.g5x-39ykz) {
  d: path("M3 3H21M3 21H21M3 12H5M19 12H21");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
