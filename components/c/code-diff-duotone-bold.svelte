<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qcetzob3x"/><path class="xazd95bpp"/><path class="mlwueibtu"/><path class="msooxxbqf"/><path class="nm1tlbreh"/><path class="e03jjq99j"/><path class="emvotkb4z"/><path class="m26ojxb3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:code-diff-duotone-bold" {...props}></Icon>
<style>
:global(.e03jjq99j) {
  d: path("M4 7h6");
}

:global(.emvotkb4z) {
  d: path("M4 20 20 4");
}

:global(.m26ojxb3w) {
  d: path("M14 17h6");
}

:global(.mlwueibtu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20 20 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.msooxxbqf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 17h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nm1tlbreh) {
  d: path("M7 4v6");
}

:global(.qcetzob3x) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 4v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xazd95bpp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
