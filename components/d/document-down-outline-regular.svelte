<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="abnm6smsv"/><path class="hqoi59sxr"/><path class="p9jmvgbqq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:document-down-outline-regular" {...props}></Icon>
<style>
:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.hqoi59sxr) {
  d: path("M12 9v7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p9jmvgbqq) {
  d: path("M9.5 13.5 12 16l2.5 -2.5");
}

</style>
