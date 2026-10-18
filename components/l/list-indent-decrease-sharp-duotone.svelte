<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hl649zb0c"/><path class="spmdglbzj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-indent-decrease-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.hl649zb0c) {
  stroke-opacity: 0.4;
  d: path("M9 12L2 12M5.2929 8.7071L2 12L5.2929 15.2929");
}

:global(.spmdglbzj) {
  d: path("M11 6L23 6M11 12L23 12M11 18L23 18");
}

</style>
