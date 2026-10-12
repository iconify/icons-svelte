<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="uva_accpf"/><circle class="o2ojnnbap"/><circle class="oy91ely1a"/><circle class="muwu9uvyd"/><circle class="joyo2ddzr"/><circle class="r27_c8b6j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:drag-handle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.joyo2ddzr) {
  cx: 9px;
  cy: 18.5px;
  r: 1.25px;
}

:global(.muwu9uvyd) {
  cx: 15px;
  cy: 12px;
  r: 1.25px;
}

:global(.o2ojnnbap) {
  cx: 15px;
  cy: 5.5px;
  r: 1.25px;
}

:global(.oy91ely1a) {
  cx: 9px;
  cy: 12px;
  r: 1.25px;
}

:global(.r27_c8b6j) {
  cx: 15px;
  cy: 18.5px;
  r: 1.25px;
}

:global(.uva_accpf) {
  cx: 9px;
  cy: 5.5px;
  r: 1.25px;
}

</style>
