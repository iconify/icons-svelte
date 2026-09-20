<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rg1-sjb4a"/><path class="ojcjn_j1b"/><path class="y93qarhow"/><path class="strt8mboj"/><path class="d8cg8bc8o"/><path class="qsb3g-bwo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coffee-machine-duotone-regular" {...props}></Icon>
<style>
:global(.d8cg8bc8o) {
  d: path("M12 13v2.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ojcjn_j1b) {
  fill: currentColor;
  d: path("M8 16h8v3a4 4 0 0 1 -8 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qsb3g-bwo) {
  d: path("M8 16h8v3a4 4 0 0 1 -8 0Z");
}

:global(.rg1-sjb4a) {
  fill: currentColor;
  d: path("M4 6a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.strt8mboj) {
  d: path("M7 8h6");
}

:global(.y93qarhow) {
  d: path("M4 6a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
