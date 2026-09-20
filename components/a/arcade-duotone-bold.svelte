<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ah1ap4vpp"/><path class="ubeu0jbbs"/><path class="k08v31p7k"/><path class="gp76xqbkg"/><path class="yvgc3wkxj"/><path class="atyo14tkp"/><path class="i6r7zygac"/><path class="fjiurnzxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arcade-duotone-bold" {...props}></Icon>
<style>
:global(.ah1ap4vpp) {
  fill: currentColor;
  d: path("M5 21V5h14v16Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.atyo14tkp) {
  d: path("M8 8h8v5H8Z");
}

:global(.fjiurnzxd) {
  d: path("M12 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gp76xqbkg) {
  fill: currentColor;
  d: path("M12 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.i6r7zygac) {
  d: path("M8 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.k08v31p7k) {
  fill: currentColor;
  d: path("M8 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

:global(.ubeu0jbbs) {
  fill: currentColor;
  d: path("M8 8h8v5H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yvgc3wkxj) {
  d: path("M5 21V5h14v16Z");
}

</style>
