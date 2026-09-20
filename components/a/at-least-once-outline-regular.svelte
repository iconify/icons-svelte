<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n7d250moc"/><path class="it83nbbll"/><path class="t4ju69b0v"/><path class="c_qwi1bzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:at-least-once-outline-regular" {...props}></Icon>
<style>
:global(.c_qwi1bzg) {
  d: path("m14 14 2 2 3.5 -3.5");
}

:global(.it83nbbll) {
  d: path("M5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.n7d250moc) {
  d: path("M3 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t4ju69b0v) {
  d: path("m12 9 2 2 3.5 -3.5");
}

</style>
