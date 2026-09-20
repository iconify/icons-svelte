<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qecovn3xi"/><path class="jz0b4rbqp"/><path class="st2iv5bfu"/><path class="h55f46bdv"/><path class="kj68giyfr"/><path class="ktrpk1wvf"/><path class="kn0tcm93r"/><path class="k5nz3bcao"/><path class="fg8libqda"/><path class="pw61xnbei"/><path class="w7fxcjk_f"/><path class="l_raegbyq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:git-pull-request-create-duotone-bold" {...props}></Icon>
<style>
:global(.fg8libqda) {
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.h55f46bdv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 7.5v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jz0b4rbqp) {
  fill: currentColor;
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.k5nz3bcao) {
  d: path("M6 7.5v9");
}

:global(.kj68giyfr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 4v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kn0tcm93r) {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ktrpk1wvf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15.5 6.5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l_raegbyq) {
  d: path("M15.5 6.5h5");
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

:global(.w7fxcjk_f) {
  d: path("M18 4v5");
}

</style>
