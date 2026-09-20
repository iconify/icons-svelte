<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="szyef5b0i"/><path class="khevvbcdr"/><path class="g-19mto8o"/><path class="fspoztu7c"/><path class="nzulwvdch"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dance-outline-thin" {...props}></Icon>
<style>
:global(.fspoztu7c) {
  d: path("m13 14 -5 5");
}

:global(.g-19mto8o) {
  d: path("m9 7 4 4 4 -4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.khevvbcdr) {
  d: path("M13 8v6");
}

:global(.nzulwvdch) {
  d: path("m13 14 5 5");
}

:global(.szyef5b0i) {
  d: path("M10 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
