<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vygtdmb5w"/><path class="zl5hlnbpt"/><path class="r_68xabcj"/><path class="jje0epbum"/><path class="kfdmhd64i"/><path class="e4btx4zel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flaky-test-duotone-thin" {...props}></Icon>
<style>
:global(.e4btx4zel) {
  d: path("m21 15 -6 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jje0epbum) {
  d: path("m3 7 3 3 5 -5");
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.r_68xabcj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21 15 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vygtdmb5w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 7 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zl5hlnbpt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
