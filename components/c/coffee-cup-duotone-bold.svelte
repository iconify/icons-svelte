<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p7a1plr7m"/><path class="ogd2aqb2f"/><path class="w001vzx2v"/><path class="zkx1g3b3t"/><path class="ghpezkxlh"/><path class="v3xsaib0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coffee-cup-duotone-bold" {...props}></Icon>
<style>
:global(.ghpezkxlh) {
  d: path("M15 7a3 3 0 0 1 0 6");
}

:global(.ogd2aqb2f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 7a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p7a1plr7m) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 7v9h11V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v3xsaib0o) {
  d: path("M2 19h15");
}

:global(.w001vzx2v) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zkx1g3b3t) {
  d: path("M4 7v9h11V7");
}

</style>
