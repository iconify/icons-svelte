<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sb2rh4bje"/><path class="j-poo7bsp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:archive-duocolor-sharp" {...props}></Icon>
<style>
:global(.j-poo7bsp) {
  d: path("M5 8v12h14V8m-9 4h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sb2rh4bje) {
  stroke-opacity: 0.4;
  d: path("M3 4h18v4H3Z");
}

</style>
