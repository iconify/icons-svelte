<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gcy6xobcc"/><path class="bxyh6cbnl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:colour-mix-outline-bold" {...props}></Icon>
<style>
:global(.bxyh6cbnl) {
  d: path("M9 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.gcy6xobcc) {
  d: path("M3 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
