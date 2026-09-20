<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="e_6o-gbms"/><path class="h857n5bhq"/><path class="qrffjub9u"/><path class="t164-vbgd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:confidence-threshold-outline-thin" {...props}></Icon>
<style>
:global(.e_6o-gbms) {
  d: path("M6 10h13");
}

:global(.h857n5bhq) {
  d: path("M8 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.qrffjub9u) {
  d: path("M12 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.t164-vbgd) {
  d: path("M16 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
