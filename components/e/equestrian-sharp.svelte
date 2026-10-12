<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wq1vi6y4e"/><path class="x8232_bgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:equestrian-sharp" {...props}></Icon>
<style>
:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.wq1vi6y4e) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.25 2.75l2.25 2.5c3 1.75 5 5.75 5 10.25v5.75H11l.25-6l-.857-.286L8.25 16.25l-2.25 1l-3.036 1.214l.536-3.214l.25-1.75l.333-1.333L5.25 11L11 5.25Z");
}

:global(.x8232_bgk) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8.75h.01");
}

</style>
