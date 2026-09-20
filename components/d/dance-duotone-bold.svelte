<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="eee7_5ben"/><path class="szyef5b0i"/><path class="khevvbcdr"/><path class="g-19mto8o"/><path class="fspoztu7c"/><path class="nzulwvdch"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dance-duotone-bold" {...props}></Icon>
<style>
:global(.eee7_5ben) {
  fill: currentColor;
  d: path("M10 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fspoztu7c) {
  d: path("m13 14 -5 5");
}

:global(.g-19mto8o) {
  d: path("m9 7 4 4 4 -4");
}

:global(.khevvbcdr) {
  d: path("M13 8v6");
}

:global(.nzulwvdch) {
  d: path("m13 14 5 5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.szyef5b0i) {
  d: path("M10 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
