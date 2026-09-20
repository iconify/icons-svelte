<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sau_nibrh"/><path class="ykmyh8b9g"/><path class="gssdzduao"/><path class="tu-7id0rh"/><path class="gl3o38_gx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flower-outline-regular" {...props}></Icon>
<style>
:global(.gl3o38_gx) {
  d: path("M8 21h8");
}

:global(.gssdzduao) {
  d: path("M5 18c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sau_nibrh) {
  d: path("M7.5 7a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.tu-7id0rh) {
  d: path("M13 18c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

:global(.ykmyh8b9g) {
  d: path("M12 11.5V21");
}

</style>
