<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tqe2jhbja"/><path class="pzyzl_b-w"/><path class="t87ohzbeq"/><path class="s7eyaw7qq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pause-duotone-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pzyzl_b-w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s7eyaw7qq) {
  d: path("M15 4v16");
}

:global(.t87ohzbeq) {
  d: path("M9 4v16");
}

:global(.tqe2jhbja) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
