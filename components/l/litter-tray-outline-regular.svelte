<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b1af8dhgl"/><path class="vhnbtvbtn"/><path class="teamv5bhf"/><path class="yegul17ht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:litter-tray-outline-regular" {...props}></Icon>
<style>
:global(.b1af8dhgl) {
  d: path("M5 8v10h14V8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.teamv5bhf) {
  d: path("M8 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.yegul17ht) {
  d: path("M14 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
