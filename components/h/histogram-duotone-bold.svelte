<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lng9-b2ib"/><path class="yavoltb2n"/><path class="b6e35tlvq"/><path class="rjja_4s_c"/><path class="pxegjhbip"/><path class="hpm6v1-ys"/><path class="dp6dvchmk"/><path class="p86p59b-c"/><path class="r7xk8o29f"/><path class="h7eeppe6g"/><path class="gkowgccsl"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:histogram-duotone-bold" {...props}></Icon>
<style>
:global(.b6e35tlvq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dp6dvchmk) {
  d: path("M4 12v8");
}

:global(.gkowgccsl) {
  d: path("M20 14v6");
}

:global(.h7eeppe6g) {
  d: path("M16 9v11");
}

:global(.hpm6v1-ys) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.lng9-b2ib) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p86p59b-c) {
  d: path("M8 7v13");
}

:global(.pxegjhbip) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.rjja_4s_c) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 9v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yavoltb2n) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 7v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
