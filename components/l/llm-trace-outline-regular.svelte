<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="crv4i00bu"/><path class="nfb4ipisv"/><path class="b603-acaz"/><path class="pqv-otbrp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:llm-trace-outline-regular" {...props}></Icon>
<style>
:global(.b603-acaz) {
  d: path("M10 12h8");
}

:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.nfb4ipisv) {
  d: path("M7 7h7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pqv-otbrp) {
  d: path("M13 17h8");
}

</style>
