<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h3k3f5whw"/><path class="cmaa2qbld"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:megaphone-duocolor-sharp" {...props}></Icon>
<style>
:global(.cmaa2qbld) {
  d: path("m11 8l10-5v16l-10-5zm0 0H3v6h8");
}

:global(.h3k3f5whw) {
  stroke-opacity: 0.4;
  d: path("M5 14v7h4v-7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
