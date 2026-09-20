<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="e71sokbbi"/><path class="sb7rl7wyu"/><path class="pt73j1ikv"/><path class="yo-0d--rc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-column-stacked-outline-regular" {...props}></Icon>
<style>
:global(.e71sokbbi) {
  d: path("M9 12v8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.pt73j1ikv) {
  d: path("M15 14v6");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.sb7rl7wyu) {
  d: path("M9 6v3");
}

:global(.yo-0d--rc) {
  d: path("M15 8v3");
}

</style>
