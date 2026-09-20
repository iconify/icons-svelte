<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t1sjjacis"/><path class="czkname1g"/><path class="g06ri4k9s"/><path class="bos0j4biy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gymnastics-outline-regular" {...props}></Icon>
<style>
:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.czkname1g) {
  d: path("M8 7c5 0 9 4 9 9");
}

:global(.g06ri4k9s) {
  d: path("m17 16 3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t1sjjacis) {
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
