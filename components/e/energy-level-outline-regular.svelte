<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nzfvycb-k"/><path class="r182r524c"/><path class="c7z9o8buo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:energy-level-outline-regular" {...props}></Icon>
<style>
:global(.c7z9o8buo) {
  d: path("M7 15h10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nzfvycb-k) {
  d: path("M7 4h10v17H7Z");
}

:global(.r182r524c) {
  d: path("M7 9h10");
}

</style>
