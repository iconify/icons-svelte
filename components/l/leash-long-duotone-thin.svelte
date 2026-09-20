<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dnge47ydj"/><path class="s74cfob_f"/><path class="ahz9fzb-m"/><path class="ttbqujc9j"/><path class="m1k1s7nte"/><path class="gyi-tobvb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:leash-long-duotone-thin" {...props}></Icon>
<style>
:global(.ahz9fzb-m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dnge47ydj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.69 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gyi-tobvb) {
  d: path("M20 5v14");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m1k1s7nte) {
  d: path("M10 12h10");
}

:global(.s74cfob_f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ttbqujc9j) {
  d: path("M7.69 8.37a4 4 0 1 1 -3.38 0");
}

</style>
