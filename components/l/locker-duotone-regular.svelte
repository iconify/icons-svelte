<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zwjmk5b0j"/><path class="n7t0anb5n"/><path class="z3eyrdd0c"/><path class="vrecxx6kh"/><path class="jlfjgzbqx"/><path class="y6kfzfgng"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:locker-duotone-regular" {...props}></Icon>
<style>
:global(.jlfjgzbqx) {
  d: path("M9 9h6");
}

:global(.n7t0anb5n) {
  fill: currentColor;
  d: path("M14 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vrecxx6kh) {
  d: path("M9 6h6");
}

:global(.y6kfzfgng) {
  d: path("M14 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.z3eyrdd0c) {
  d: path("M6 4a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

:global(.zwjmk5b0j) {
  fill: currentColor;
  d: path("M6 4a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
