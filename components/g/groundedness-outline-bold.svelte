<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="duxy6wbvl"/><path class="ok9ioqb8x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:groundedness-outline-bold" {...props}></Icon>
<style>
:global(.duxy6wbvl) {
  d: path("m7 9 4 4 6 -6");
}

:global(.ok9ioqb8x) {
  d: path("M4 17h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
