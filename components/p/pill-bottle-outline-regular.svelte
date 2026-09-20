<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t69363l7x"/><path class="q_br9pbky"/><path class="ptaeireto"/><path class="e8vupfb9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pill-bottle-outline-regular" {...props}></Icon>
<style>
:global(.e8vupfb9c) {
  d: path("M9.5 14h5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ptaeireto) {
  d: path("M12 11.5v5");
}

:global(.q_br9pbky) {
  d: path("M8 8V4h8v4");
}

:global(.t69363l7x) {
  d: path("M6 8v13h12V8Z");
}

</style>
