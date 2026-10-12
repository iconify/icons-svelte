<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="eixp8sb5w"/><path class="urjkyporg"/><path class="ujk2d4bbq"/><circle class="hxly0r3mq"/><circle class="prxayub-e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dish-soap" {...props}></Icon>
<style>
:global(.eixp8sb5w) {
  width: 3.5px;
  height: 4px;
  x: 10.25px;
  y: 4.25px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hxly0r3mq) {
  cx: 18.75px;
  cy: 4.75px;
  r: 1.75px;
}

:global(.prxayub-e) {
  cx: 5.5px;
  cy: 4.25px;
  r: 1.25px;
}

:global(.ujk2d4bbq) {
  d: path("M12 12.25c1 1.15 1.5 2 1.5 2.65a1.5 1.5 0 0 1-3 0c0-.65.5-1.5 1.5-2.65");
}

:global(.urjkyporg) {
  d: path("M8.25 8.25h7.5a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2h-7.5a2 2 0 0 1-2-2v-9a2 2 0 0 1 2-2");
}

</style>
