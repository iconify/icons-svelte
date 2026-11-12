<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="r0xhknb7f"/><path class="c5cjgzbpf"/><path class="w6cmsvjjt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-slash-line-duotone" {...props}></Icon>
<style>
:global(.c5cjgzbpf) {
  d: path("M18.2168 18.2178L21.9994 22.0004");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r0xhknb7f) {
  cx: 11.5px;
  cy: 11.5px;
  r: 9.5px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.w6cmsvjjt) {
  d: path("M9.72852 13.2695L11.4963 11.5018L13.264 9.734");
}

</style>
