<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kf3k8pbxe"/><path class="h737ebc_s"/><path class="u4eh83btt"/><path class="yfyg0bb3p"/><path class="snqsppb6q"/><path class="atoje4bsc"/><path class="njj_4bcir"/><path class="xj193cz1p"/><path class="e948j-b5x"/><path class="pmuiqo95v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:balcony-duotone-regular" {...props}></Icon>
<style>
:global(.atoje4bsc) {
  d: path("M2 6h20");
}

:global(.e948j-b5x) {
  d: path("M18 6v11");
}

:global(.h737ebc_s) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 6v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kf3k8pbxe) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 6h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.njj_4bcir) {
  d: path("M6 6v11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pmuiqo95v) {
  d: path("M2 17h20");
}

:global(.snqsppb6q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 17h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u4eh83btt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 6v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xj193cz1p) {
  d: path("M12 6v11");
}

:global(.yfyg0bb3p) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 6v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
