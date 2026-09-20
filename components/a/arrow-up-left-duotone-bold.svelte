<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pu2676bxf"/><path class="iu2miqbwo"/><path class="pilb5jbne"/><path class="olzfpgbos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-up-left-duotone-bold" {...props}></Icon>
<style>
:global(.iu2miqbwo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 14V4h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.olzfpgbos) {
  d: path("M4 14V4h10");
}

:global(.pilb5jbne) {
  d: path("M20 20 4 4");
}

:global(.pu2676bxf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 20 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
