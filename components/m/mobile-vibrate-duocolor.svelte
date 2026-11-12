<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cbt8ot9gw"/><path class="zjq61mbnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mobile-vibrate-duocolor" {...props}></Icon>
<style>
:global(.cbt8ot9gw) {
  stroke-opacity: 0.4;
  d: path("m3 6l1 3l-1 3l1 3l-1 3M21 6l-1 3l1 3l-1 3l1 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zjq61mbnc) {
  d: path("M7 5a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2Z");
}

</style>
