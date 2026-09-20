<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n36352b2b"/><path class="j3g0obcgt"/><path class="m_ifpmwzr"/><path class="w-c31ggft"/><path class="oqfv9rb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:city-break-outline-regular" {...props}></Icon>
<style>
:global(.j3g0obcgt) {
  d: path("M13 21V4h6v17");
}

:global(.m_ifpmwzr) {
  d: path("M4 12h6");
}

:global(.n36352b2b) {
  d: path("M4 21V8h6v13");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

:global(.w-c31ggft) {
  d: path("M13 9h6");
}

</style>
