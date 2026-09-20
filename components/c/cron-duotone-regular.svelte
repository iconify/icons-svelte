<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s_h_b5yjo"/><path class="kcbq_cc5o"/><path class="v6ic8acqd"/><path class="cnjb-4b2j"/><path class="a0ad3xbzg"/><path class="v2c2asm0d"/><path class="icp673bbo"/><path class="dm5ccobgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cron-duotone-regular" {...props}></Icon>
<style>
:global(.a0ad3xbzg) {
  d: path("M12 3a9 9 0 1 0 9 9");
}

:global(.cnjb-4b2j) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dm5ccobgo) {
  d: path("M12 12h4");
}

:global(.icp673bbo) {
  d: path("M12 9v3");
}

:global(.kcbq_cc5o) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 4v5h-5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s_h_b5yjo) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3a9 9 0 1 0 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v2c2asm0d) {
  d: path("M21 4v5h-5");
}

:global(.v6ic8acqd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 9v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
