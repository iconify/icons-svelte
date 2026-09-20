<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b05td8f9z"/><path class="kzwfngmve"/><path class="yyw12k01a"/><path class="e2nq-yvbg"/><path class="cmfzxibyz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:glacier-tier-duotone-bold" {...props}></Icon>
<style>
:global(.b05td8f9z) {
  fill: currentColor;
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.cmfzxibyz) {
  d: path("M17 15v3.5");
}

:global(.e2nq-yvbg) {
  d: path("M12 15v6");
}

:global(.kzwfngmve) {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yyw12k01a) {
  d: path("M7 15v3.5");
}

</style>
