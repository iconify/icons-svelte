<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vqal-abhe"/><path class="bpdfs5b6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:health-probe-outline-bold" {...props}></Icon>
<style>
:global(.bpdfs5b6a) {
  d: path("m9 15 2 2 4 -4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vqal-abhe) {
  d: path("M3 8h4.5l2 -2 4 4 2 -2H21");
}

</style>
