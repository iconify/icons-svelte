<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="trv9mgb9o"/><path class="ru5ha2bbk"/><circle class="dxmh3lbzl"/><path class="xj35lbqxs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:payroll-sharp" {...props}></Icon>
<style>
:global(.dxmh3lbzl) {
  cx: 17.25px;
  cy: 13px;
  r: 4px;
}

:global(.ru5ha2bbk) {
  d: path("M3.5 19.75h8.75V19c0-3-2.1-5.25-4.75-5.25S2.75 16 2.75 19v.75z");
}

:global(.trv9mgb9o) {
  cx: 7.5px;
  cy: 7.25px;
  r: 3px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xj35lbqxs) {
  d: path("m18.38 12.02l-.35-.75h-1.94v.86c0 1.22 2.34.61 2.34 1.78v.83h-2.018l-.292-.73");
}

</style>
