<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="i05-3-p3f"/><path class="gam3cw54g"/><path class="tee5ti87r"/><path class="ys-dg812g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:overfit-duotone-bold" {...props}></Icon>
<style>
:global(.gam3cw54g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i05-3-p3f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 9 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tee5ti87r) {
  d: path("m3 9 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
