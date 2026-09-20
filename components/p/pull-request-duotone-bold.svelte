<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qecovn3xi"/><path class="st2iv5bfu"/><path class="tx27-qd_t"/><path class="h9eb1abzf"/><path class="x2i610b-y"/><path class="kn0tcm93r"/><path class="xaitxdbcw"/><path class="brze8vkpt"/><path class="pw61xnbei"/><path class="e3ixvub0q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pull-request-duotone-bold" {...props}></Icon>
<style>
:global(.brze8vkpt) {
  d: path("M18 5v11.5");
}

:global(.e3ixvub0q) {
  d: path("m15 8 3 -3 3 3");
}

:global(.h9eb1abzf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 5v11.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kn0tcm93r) {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.pw61xnbei) {
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.qecovn3xi) {
  fill: currentColor;
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.st2iv5bfu) {
  fill: currentColor;
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tx27-qd_t) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 7.5V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x2i610b-y) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 8 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xaitxdbcw) {
  d: path("M6 7.5V21");
}

</style>
