<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khksl7boy"/><path class="ah2gkhstn"/><path class="cs9f_sbcc"/><path class="ajhfqqnbg"/><path class="h2sq3fbpa"/><path class="xgrfb-bqu"/><path class="o759xmblc"/><path class="h7bcztycq"/><path class="c27cgq4un"/><path class="xyj-l9cjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:normalize-duotone-bold" {...props}></Icon>
<style>
:global(.ah2gkhstn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ajhfqqnbg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c27cgq4un) {
  d: path("M18 8v8");
}

:global(.cs9f_sbcc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h2sq3fbpa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h7bcztycq) {
  d: path("M12 8v8");
}

:global(.khksl7boy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o759xmblc) {
  d: path("M6 8v8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
