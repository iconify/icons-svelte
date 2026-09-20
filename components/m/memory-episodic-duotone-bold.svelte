<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="dk7t6bbsy"/><path class="qn-opib9b"/><path class="hbj8cbc9s"/><path class="r3faxubne"/><path class="be1u5t58a"/><path class="h50arts9k"/><path class="ojg4edcfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-episodic-duotone-bold" {...props}></Icon>
<style>
:global(.be1u5t58a) {
  d: path("M6 8h14");
}

:global(.dh-nlhghu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dk7t6bbsy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 8h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h50arts9k) {
  d: path("M6 12h10");
}

:global(.hbj8cbc9s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 16h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ojg4edcfp) {
  d: path("M6 16h14");
}

:global(.qn-opib9b) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 12h10");
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

</style>
