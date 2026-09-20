<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mzsthfbrb"/><path class="y7cs2bcxe"/><path class="nzpsuduik"/><path class="ae-e09b3w"/><path class="j8_8pdbyc"/><path class="h7j2x7b-d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:holiday-apartment-duotone-bold" {...props}></Icon>
<style>
:global(.ae-e09b3w) {
  d: path("M3 12h18");
}

:global(.h7j2x7b-d) {
  d: path("M14 15h5v4h-5Z");
}

:global(.j8_8pdbyc) {
  d: path("M12 3v9");
}

:global(.mzsthfbrb) {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nzpsuduik) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.y7cs2bcxe) {
  fill: currentColor;
  d: path("M14 15h5v4h-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
