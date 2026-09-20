<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yvgc3wkxj"/><path class="elmoo_bpw"/><path class="q518x4bkb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:front-door-outline-bold" {...props}></Icon>
<style>
:global(.elmoo_bpw) {
  d: path("M15 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.q518x4bkb) {
  d: path("M5 9h14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yvgc3wkxj) {
  d: path("M5 21V5h14v16Z");
}

</style>
