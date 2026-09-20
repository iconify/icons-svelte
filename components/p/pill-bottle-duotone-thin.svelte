<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yerw84_9m"/><path class="t69363l7x"/><path class="q_br9pbky"/><path class="ptaeireto"/><path class="e8vupfb9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pill-bottle-duotone-thin" {...props}></Icon>
<style>
:global(.e8vupfb9c) {
  d: path("M9.5 14h5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
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

:global(.yerw84_9m) {
  fill: currentColor;
  d: path("M6 8v13h12V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
