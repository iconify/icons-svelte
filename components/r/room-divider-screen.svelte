<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eztxrab2o"/><path class="ufhpgbcsi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:room-divider-screen" {...props}></Icon>
<style>
:global(.eztxrab2o) {
  d: path("M3 18.5V4l6 2l6-2l6 2v14.5");
}

:global(.ufhpgbcsi) {
  d: path("m3 16l6 2l6-2l6 2M9 6v14.5M15 4v14.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
