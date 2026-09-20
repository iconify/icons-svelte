<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qoibgxtiv"/><path class="vgxm_rbmc"/><path class="rtzyu2rle"/><path class="nn3mbubli"/><path class="uw5kuce7r"/><path class="j41x8568l"/><path class="zdse1fb0u"/><path class="cfq8fpb9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:align-left-obj-duotone-bold" {...props}></Icon>
<style>
:global(.cfq8fpb9k) {
  d: path("M5.5 17H12");
}

:global(.j41x8568l) {
  d: path("M5.5 7H15");
}

:global(.nn3mbubli) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.5 17H12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qoibgxtiv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rtzyu2rle) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.5 12H19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uw5kuce7r) {
  d: path("M3 3v18");
}

:global(.vgxm_rbmc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.5 7H15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zdse1fb0u) {
  d: path("M5.5 12H19");
}

</style>
