<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yomj0bbqc"/><path class="ay19-ob6x"/><path class="bos0j4biy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:airport-outline-regular" {...props}></Icon>
<style>
:global(.ay19-ob6x) {
  d: path("m6 9 4.5 -4.5h3L18 9");
}

:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yomj0bbqc) {
  d: path("M9 21V9h6v12");
}

</style>
