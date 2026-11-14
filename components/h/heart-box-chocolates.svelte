<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kipujjbrl"/><path class="lhn3cpxsj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:heart-box-chocolates" {...props}></Icon>
<style>
:global(.kipujjbrl) {
  d: path("M2.5 3.5h19V8h-19ZM4 8v11.5q0 1.25 1.25 1.25h13.5q1.25 0 1.25-1.25V8");
}

:global(.lhn3cpxsj) {
  d: path("m12 17.5l-3-3a2.125 2.125 0 0 1 3-3a2.125 2.125 0 0 1 3 3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
