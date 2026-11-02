<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r585ypbsk"/><path class="ot27p0b5w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:case-sensitive-duocolor-round" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ot27p0b5w) {
  d: path("M3 18L7 6l4 12m-6-4h4");
}

:global(.r585ypbsk) {
  stroke-opacity: 0.4;
  d: path("M15 15a3 3 0 1 0 6 0a3 3 0 0 0-6 0m6-3v6");
}

</style>
