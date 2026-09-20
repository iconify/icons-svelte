<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w0229ybxd"/><path class="wyy34ebaj"/><path class="c9sgi36ry"/><path class="gcalxb98a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fire-extinguisher-outline-thin" {...props}></Icon>
<style>
:global(.c9sgi36ry) {
  d: path("M16 8c3 0 4 2 4 5");
}

:global(.gcalxb98a) {
  d: path("M8 13h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w0229ybxd) {
  d: path("M8 10a4 4 0 0 1 8 0v9a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.wyy34ebaj) {
  d: path("M10 6V3.5h5");
}

</style>
