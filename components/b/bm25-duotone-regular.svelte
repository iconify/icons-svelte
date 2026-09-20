<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nb_bhac3g"/><path class="g-4ao_sjh"/><path class="f7cjbzb4e"/><path class="mvo7wtatf"/><path class="lwb2w331h"/><path class="mtcl3hbqt"/><path class="f2_a4gbcx"/><path class="s13m_784z"/><path class="he2cqebcu"/><path class="n96__jb1n"/><path class="o24qh25eq"/><path class="ov2ejkbhi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bm25-duotone-regular" {...props}></Icon>
<style>
:global(.f2_a4gbcx) {
  d: path("M2 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.f7cjbzb4e) {
  fill: currentColor;
  d: path("M2 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.g-4ao_sjh) {
  fill: currentColor;
  d: path("M2 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.he2cqebcu) {
  d: path("M2 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.lwb2w331h) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mtcl3hbqt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 17h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mvo7wtatf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 7h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n96__jb1n) {
  d: path("M6 12h11");
}

:global(.nb_bhac3g) {
  fill: currentColor;
  d: path("M2 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

:global(.o24qh25eq) {
  d: path("M2 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ov2ejkbhi) {
  d: path("M6 17h7");
}

:global(.s13m_784z) {
  d: path("M6 7h15");
}

</style>
