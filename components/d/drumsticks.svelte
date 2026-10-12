<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s0pxgjf9z"/><circle class="lmm9hoo6z"/><circle class="gx5a-ybeg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:drumsticks" {...props}></Icon>
<style>
:global(.gx5a-ybeg) {
  cx: 6.5px;
  cy: 6.5px;
  r: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lmm9hoo6z) {
  cx: 17.5px;
  cy: 6.5px;
  r: 1.5px;
}

:global(.s0pxgjf9z) {
  d: path("M4.25 20.75L16.48 7.6m3.27 13.15L7.52 7.6");
}

</style>
