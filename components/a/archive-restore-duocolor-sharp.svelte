<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eozf1-bjg"/><path class="ii4dpm58l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:archive-restore-duocolor-sharp" {...props}></Icon>
<style>
:global(.eozf1-bjg) {
  stroke-opacity: 0.4;
  d: path("m15 14l-3-3l-3 3m3-3v6");
}

:global(.ii4dpm58l) {
  d: path("M3 4h18v4H3Zm2 4v12h14V8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
