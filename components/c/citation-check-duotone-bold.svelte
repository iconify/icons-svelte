<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g45-xubrp"/><path class="s2ely3boa"/><path class="d_am44b9l"/><path class="fyea5htjc"/><path class="c4axibc2h"/><path class="uo9ro-b5p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:citation-check-duotone-bold" {...props}></Icon>
<style>
:global(.c4axibc2h) {
  d: path("M8 3v4");
}

:global(.d_am44b9l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 14 5 5L20 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fyea5htjc) {
  d: path("M4 3v4");
}

:global(.g45-xubrp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s2ely3boa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 3v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uo9ro-b5p) {
  d: path("m4 14 5 5L20 8");
}

</style>
