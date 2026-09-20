<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bc38ssbmv"/><path class="r7xk8o29f"/><path class="nxg78fr6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flip-h-outline-bold" {...props}></Icon>
<style>
:global(.bc38ssbmv) {
  d: path("m3 6 6 6 -6 6Z");
}

:global(.nxg78fr6n) {
  d: path("m21 6 -6 6 6 6Z");
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
