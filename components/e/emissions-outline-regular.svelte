<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wfp94ccxr"/><path class="spiam7zpy"/><path class="bx6cs-b9q"/><path class="nt1osdoki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:emissions-outline-regular" {...props}></Icon>
<style>
:global(.bx6cs-b9q) {
  d: path("M16 3.5a2.5 2.5 0 0 1 0 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nt1osdoki) {
  d: path("M14 21h7");
}

:global(.spiam7zpy) {
  d: path("M16 13.5a2.5 2.5 0 0 1 0 -5");
}

:global(.wfp94ccxr) {
  d: path("M6 21V11h6v10Z");
}

</style>
