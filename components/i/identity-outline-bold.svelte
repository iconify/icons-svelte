<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="okud9xj_d"/><path class="skpdqenaf"/><path class="f69zonn4h"/><path class="epa94wwve"/><path class="j3tm7xb5y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:identity-outline-bold" {...props}></Icon>
<style>
:global(.epa94wwve) {
  d: path("M14 11h6");
}

:global(.f69zonn4h) {
  d: path("M4 17a4 4 0 0 1 8 0");
}

:global(.j3tm7xb5y) {
  d: path("M14 15h4");
}

:global(.okud9xj_d) {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.skpdqenaf) {
  d: path("M6 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
