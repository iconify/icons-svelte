<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wuixsugxy"/><path class="eqt88e7xb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lab-notebook" {...props}></Icon>
<style>
:global(.eqt88e7xb) {
  d: path("M12 6h1a1 1 0 0 1 1 1v.711a1.5 1.5 0 0 0 .107.557l1.07 2.675A1.5 1.5 0 0 1 13.784 13h-2.568a1.5 1.5 0 0 1-1.393-2.057l1.07-2.675A1.5 1.5 0 0 0 11 7.711V7a1 1 0 0 1 1-1");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wuixsugxy) {
  d: path("M5 18.5V5a2 2 0 0 1 2-2h12v13.5H7a2 2 0 0 0 0 4h12");
}

</style>
