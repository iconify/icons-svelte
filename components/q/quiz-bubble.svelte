<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="g6ctus9qt"/><circle class="amfo-fh-v"/><circle class="kdylvcbxp"/><path class="loy81tbxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:quiz-bubble" {...props}></Icon>
<style>
:global(.amfo-fh-v) {
  cx: 8.25px;
  cy: 8.5px;
  r: 1.5px;
}

:global(.g6ctus9qt) {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kdylvcbxp) {
  cx: 8.25px;
  cy: 15.5px;
  r: 1.5px;
}

:global(.loy81tbxd) {
  d: path("M12 8.5h4.5m-4.5 7h4.5");
}

</style>
