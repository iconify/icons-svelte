<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r3faxubne"/><path class="rxxtm7qkj"/><path class="einbtqqgb"/><path class="mldnorr-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:index-outline-regular" {...props}></Icon>
<style>
:global(.einbtqqgb) {
  d: path("M7 12h13");
}

:global(.mldnorr-p) {
  d: path("M7 17h13");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.rxxtm7qkj) {
  d: path("M7 7h13");
}

</style>
