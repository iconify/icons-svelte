<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ylas06exf"/><path class="gob4qybps"/><path class="a-4h4yxxq"/><path class="mc2u6golu"/><path class="s2a0oqbtm"/><path class="c4e1y7wvc"/><path class="h36909btm"/><path class="rzbbkyb0w"/><path class="a76nyxbck"/><path class="i7lk_63qj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:circuit-open-duotone-bold" {...props}></Icon>
<style>
:global(.a-4h4yxxq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 5v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.a76nyxbck) {
  d: path("M18 14v5");
}

:global(.c4e1y7wvc) {
  d: path("M4 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gob4qybps) {
  fill: currentColor;
  d: path("M16 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.h36909btm) {
  d: path("M16 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.i7lk_63qj) {
  d: path("m8 12 6 -6");
}

:global(.mc2u6golu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 14v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rzbbkyb0w) {
  d: path("M6 5v5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s2a0oqbtm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 12 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ylas06exf) {
  fill: currentColor;
  d: path("M4 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
