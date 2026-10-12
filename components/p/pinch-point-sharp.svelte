<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="hsr8babyg"/><circle class="dqeji9_-y"/><path class="j60y2_bjy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pinch-point-sharp" {...props}></Icon>
<style>
:global(.dqeji9_-y) {
  cx: 16px;
  cy: 15.5px;
  r: 2.5px;
}

:global(.hsr8babyg) {
  cx: 8px;
  cy: 15.5px;
  r: 2.5px;
}

:global(.j60y2_bjy) {
  d: path("M12 4.5v7m-2-2l2 2l2-2");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
