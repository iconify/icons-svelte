<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nkim8cbjd"/><path class="azgrucbqu"/><path class="j5yfc7b4j"/><path class="btdmtu_xg"/><path class="vckqcjbbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:barcode-outline-regular" {...props}></Icon>
<style>
:global(.azgrucbqu) {
  d: path("M7 5v14");
}

:global(.btdmtu_xg) {
  d: path("M14 5v14");
}

:global(.j5yfc7b4j) {
  d: path("M11 5v14");
}

:global(.nkim8cbjd) {
  d: path("M4 5v14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vckqcjbbb) {
  d: path("M18 5v14");
}

</style>
