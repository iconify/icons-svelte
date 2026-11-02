<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n93wedc1i"/><path class="pj7u6z6_k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:door-duocolor-sharp" {...props}></Icon>
<style>
:global(.n93wedc1i) {
  stroke-opacity: 0.4;
  d: path("M14 12h.01");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pj7u6z6_k) {
  d: path("M3 21h18M6 21V3h12v18");
}

</style>
