<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="ln_5yacac"/><path class="qnqxdbb_t"/><path class="nkqguac9f"/><path class="g91uwsb-i"/><path class="r3faxubne"/><path class="ler50rfbf"/><path class="siun7_bal"/><path class="cub64ac5a"/><path class="cjsg0ab2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:retention-duotone-bold" {...props}></Icon>
<style>
:global(.cjsg0ab2y) {
  d: path("M2 20h20");
}

:global(.cub64ac5a) {
  d: path("M19 13v7");
}

:global(.dh-nlhghu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g91uwsb-i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ler50rfbf) {
  d: path("M9 8v12");
}

:global(.ln_5yacac) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nkqguac9f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 13v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qnqxdbb_t) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.siun7_bal) {
  d: path("M14 11v9");
}

</style>
