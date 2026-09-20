<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xnf-8e_tt"/><path class="cm2w_7k0o"/><path class="v9n4_syfk"/><path class="intvnpcjd"/><path class="a0ad3xbzg"/><path class="v2c2asm0d"/><path class="icp673bbo"/><path class="dm5ccobgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cron-duotone-bold" {...props}></Icon>
<style>
:global(.a0ad3xbzg) {
  d: path("M12 3a9 9 0 1 0 9 9");
}

:global(.cm2w_7k0o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 4v5h-5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dm5ccobgo) {
  d: path("M12 12h4");
}

:global(.icp673bbo) {
  d: path("M12 9v3");
}

:global(.intvnpcjd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v2c2asm0d) {
  d: path("M21 4v5h-5");
}

:global(.v9n4_syfk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xnf-8e_tt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3a9 9 0 1 0 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
