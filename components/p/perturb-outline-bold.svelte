<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ozi-k-boi"/><path class="ph2id7bdf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:perturb-outline-bold" {...props}></Icon>
<style>
:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

:global(.ph2id7bdf) {
  d: path("m3 15 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
