<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xfi3j1flh"/><path class="uome7fb7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:check-broken" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uome7fb7d) {
  d: path("M16.5 9.5L19 7");
}

:global(.xfi3j1flh) {
  stroke-linejoin: round;
  d: path("M14 12L9 17L5 13");
}

</style>
