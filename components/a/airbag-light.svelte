<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rcl5bg80n"/><path class="cbmkxtsqe"/><circle class="c7ai1sd8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:airbag-light" {...props}></Icon>
<style>
:global(.c7ai1sd8z) {
  cx: 17.25px;
  cy: 7.5px;
  r: 3.75px;
}

:global(.cbmkxtsqe) {
  d: path("M6.75 9.75h2q1 0 1.23.97l.54 2.31q.23.97 1.23.97H15q1 0 1.17.99l.91 5.27q.17.99-.83.99h-1q-1 0-1.23-.97l-.54-2.31q-.23-.97-1.23-.97H8.5q-1 0-1.28-.96l-1.19-4.08q-.28-.96-.28-1.58q0-.63 1-.63");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rcl5bg80n) {
  cx: 7.75px;
  cy: 5px;
  r: 2.25px;
}

</style>
