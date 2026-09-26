<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="by26kkbis"/><path class="rnu_b9b5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-align-offset-bottom-sharp" {...props}></Icon>
<style>
:global(.by26kkbis) {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4771 22 2 17.5228 2 12C2 6.4771 6.4771 2 12 2C17.5228 2 22 6.4771 22 12Z");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rnu_b9b5a) {
  d: path("M7 16L14 16M8 12L17 12M13 8L17 8");
}

</style>
