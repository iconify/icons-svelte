<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eozf1-bjg"/><path class="ud6ldhuuk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:archive-restore-duocolor" {...props}></Icon>
<style>
:global(.eozf1-bjg) {
  stroke-opacity: 0.4;
  d: path("m15 14l-3-3l-3 3m3-3v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ud6ldhuuk) {
  d: path("M3 6a2 2 0 0 1 2-2h14a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2m2 2v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V8");
}

</style>
