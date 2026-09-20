<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lmauonb1j"/><path class="faaxtxspp"/><path class="wdpkdo6us"/><path class="w0as59itk"/><path class="jlfjgzbqx"/><path class="aum97lbyp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:draft-duotone-bold" {...props}></Icon>
<style>
:global(.aum97lbyp) {
  d: path("M9 13h4");
}

:global(.faaxtxspp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jlfjgzbqx) {
  d: path("M9 9h6");
}

:global(.lmauonb1j) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 3H6v18h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w0as59itk) {
  d: path("M13 3H6v18h8");
}

:global(.wdpkdo6us) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 13h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
