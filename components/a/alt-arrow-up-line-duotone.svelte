<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s_mr-hbpj"/><path class="yj0yf9o2f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-up-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s_mr-hbpj) {
  d: path("M19 15L12 9L5 15");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.yj0yf9o2f) {
  d: path("M8.5 12L12 9L19 15");
}

</style>
