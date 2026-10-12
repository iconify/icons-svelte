<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rna0n-spg"/><rect class="q2-m9pbth"/><rect class="c4m440bqj"/><rect class="fi9pf09om"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:monorepo" {...props}></Icon>
<style>
:global(.c4m440bqj) {
  width: 3px;
  height: 3px;
  x: 10.5px;
  y: 11.5px;
  rx: 0.75px;
}

:global(.fi9pf09om) {
  width: 3px;
  height: 3px;
  x: 16px;
  y: 11.5px;
  rx: 0.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q2-m9pbth) {
  width: 3px;
  height: 3px;
  x: 5px;
  y: 11.5px;
  rx: 0.75px;
}

:global(.rna0n-spg) {
  d: path("M2.75 7.25a2.5 2.5 0 0 1 2.5-2.5h3.6a2 2 0 0 1 1.6.8L11.55 7a2 2 0 0 0 1.6.8h5.6a2.5 2.5 0 0 1 2.5 2.5v6.45a2.5 2.5 0 0 1-2.5 2.5H5.25a2.5 2.5 0 0 1-2.5-2.5Z");
}

</style>
