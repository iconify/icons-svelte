<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eq8p65fcb"/><path class="sxlwlmkmh"/><path class="r7xk8o29f"/><path class="sjot3p-qh"/><path class="n_pijqp-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:crossword-outline-thin" {...props}></Icon>
<style>
:global(.eq8p65fcb) {
  d: path("M4 4v16h16V4Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n_pijqp-h) {
  d: path("M14 16h4");
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.sjot3p-qh) {
  d: path("M6 8h4");
}

:global(.sxlwlmkmh) {
  d: path("M4 12h16");
}

</style>
