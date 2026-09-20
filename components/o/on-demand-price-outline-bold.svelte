<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nnzlfsekh"/><path class="teszqoqtj"/><path class="zqsgc7abe"/><path class="enrpg0aoq"/><path class="icp673bbo"/><path class="tbr41ebiu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:on-demand-price-outline-bold" {...props}></Icon>
<style>
:global(.enrpg0aoq) {
  d: path("M9 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.icp673bbo) {
  d: path("M12 9v3");
}

:global(.nnzlfsekh) {
  d: path("M2 8a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tbr41ebiu) {
  d: path("M12 12h2.5");
}

:global(.teszqoqtj) {
  d: path("M5.5 10.5v3");
}

:global(.zqsgc7abe) {
  d: path("M18.5 10.5v3");
}

</style>
