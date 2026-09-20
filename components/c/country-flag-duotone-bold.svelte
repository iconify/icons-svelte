<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gj046xfnq"/><path class="smaijss-l"/><path class="lwtn6xthc"/><path class="a_-94rbje"/><path class="f9uxp9ptq"/><path class="he6k4tqrw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:country-flag-duotone-bold" {...props}></Icon>
<style>
:global(.a_-94rbje) {
  d: path("M5 2v20");
}

:global(.f9uxp9ptq) {
  d: path("M5 4h14v9H5");
}

:global(.gj046xfnq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.he6k4tqrw) {
  d: path("M5 8.5h14");
}

:global(.lwtn6xthc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 8.5h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.smaijss-l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 4h14v9H5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
