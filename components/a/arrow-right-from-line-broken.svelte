<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bjr4uf7pk"/><path class="ymvg5pbqm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-from-line-broken" {...props}></Icon>
<style>
:global(.bjr4uf7pk) {
  d: path("M3 4L3 8M3 12L3 20");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ymvg5pbqm) {
  d: path("M8 12L21 12M16.625 8L21 12L16.625 16");
}

</style>
