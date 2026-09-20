<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k-sgg11ok"/><path class="bwxeoibzi"/><path class="x1_r36phd"/><path class="ct75s-bnk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:migrate-outline-bold" {...props}></Icon>
<style>
:global(.bwxeoibzi) {
  d: path("M15 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

:global(.ct75s-bnk) {
  d: path("m12 9 3 3 -3 3");
}

:global(.k-sgg11ok) {
  d: path("M2 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x1_r36phd) {
  d: path("M9 12h6");
}

</style>
