<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="atz95bbsm"/><path class="qa-jr78us"/><path class="vdu53hb5w"/><path class="jje0epbum"/><path class="kfdmhd64i"/><path class="e4btx4zel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flaky-test-duotone-regular" {...props}></Icon>
<style>
:global(.atz95bbsm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 7 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e4btx4zel) {
  d: path("m21 15 -6 6");
}

:global(.jje0epbum) {
  d: path("m3 7 3 3 5 -5");
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qa-jr78us) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vdu53hb5w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m21 15 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
