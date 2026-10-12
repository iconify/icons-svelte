<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="xn-0agmvk"/><path class="hu6c6ebjx"/><circle class="o5liqyaba"/><circle class="ox23iccdt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:girl-sharp" {...props}></Icon>
<style>
:global(.hu6c6ebjx) {
  d: path("M6.5 21.25h11.75v-.75c0-2.2-2.81-3.75-6.25-3.75S5.75 18.3 5.75 20.5v.75z");
}

:global(.o5liqyaba) {
  cx: 8.3px;
  cy: 7.6px;
  r: 1.5px;
}

:global(.ox23iccdt) {
  cx: 15.7px;
  cy: 7.6px;
  r: 1.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xn-0agmvk) {
  cx: 12px;
  cy: 10px;
  r: 3.25px;
}

</style>
