<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hy7iybk2m"/><path class="yshwovfnd"/><path class="h8oaykbcj"/><path class="mmc_38taf"/><path class="u6ajjqcac"/><path class="s_qnepbtm"/><path class="e1s2le8fv"/><path class="lmc6jyb6f"/><path class="p41-m0bke"/><path class="vg0qlegui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:list-tree-duotone-bold" {...props}></Icon>
<style>
:global(.e1s2le8fv) {
  d: path("M5 10h6");
}

:global(.h8oaykbcj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 10h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hy7iybk2m) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 3v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lmc6jyb6f) {
  d: path("M14 10h7");
}

:global(.mmc_38taf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 17h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p41-m0bke) {
  d: path("M5 17h6");
}

:global(.s_qnepbtm) {
  d: path("M5 3v14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u6ajjqcac) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 17h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vg0qlegui) {
  d: path("M14 17h7");
}

:global(.yshwovfnd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
