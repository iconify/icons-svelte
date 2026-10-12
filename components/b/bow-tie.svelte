<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iv_binu5p"/><rect class="no2rj0swx"/><path class="f0z72lkhg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bow-tie" {...props}></Icon>
<style>
:global(.f0z72lkhg) {
  d: path("M5.5 10.25v3.5m13-3.5v3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iv_binu5p) {
  d: path("m4.07 7.22l2.86 1.56Q8.25 9.5 8.25 11v2q0 1.5-1.32 2.22l-2.86 1.56q-1.32.72-1.32-.78V8q0-1.5 1.32-.78m15.86 0l-2.86 1.56q-1.32.72-1.32 2.22v2q0 1.5 1.32 2.22l2.86 1.56q1.32.72 1.32-.78V8q0-1.5-1.32-.78");
}

:global(.no2rj0swx) {
  width: 2.5px;
  height: 5.5px;
  x: 10.75px;
  y: 9.25px;
  rx: 1px;
}

</style>
