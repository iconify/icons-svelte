<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sfbfre4oy"/><path class="nm76pbt0e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:code-xml-duotone" {...props}></Icon>
<style>
:global(.nm76pbt0e) {
  d: path("M10 19L14 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sfbfre4oy) {
  stroke-opacity: 0.4;
  d: path("M6 7L2 12L6 17M18 7L22 12L18 17");
}

</style>
