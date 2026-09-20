<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kn820ue-q"/><path class="jv-yj3p-w"/><path class="crdq_-bxv"/><path class="xaz90clio"/><path class="ree9b4m7i"/><path class="pbz4y6llk"/><path class="xqz890wro"/><path class="ejtyvbbdg"/><path class="rkhcgsbdl"/><path class="t4vjq-bqk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-combo-duotone-bold" {...props}></Icon>
<style>
:global(.crdq_-bxv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 15v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ejtyvbbdg) {
  d: path("M17 15v4");
}

:global(.jv-yj3p-w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kn820ue-q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pbz4y6llk) {
  d: path("M5 13v6");
}

:global(.ree9b4m7i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 9 4 -4 4 4 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t4vjq-bqk) {
  d: path("m4 9 4 -4 4 4 4 -4 4 4");
}

:global(.xaz90clio) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xqz890wro) {
  d: path("M11 12v7");
}

</style>
