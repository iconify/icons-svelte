<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s_c1vbwpu"/><path class="rt0qgebuc"/><path class="rd9126b2a"/><path class="j1bx6i80n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:party-popper-outline-bold" {...props}></Icon>
<style>
:global(.j1bx6i80n) {
  d: path("m12 6 3 -3");
}

:global(.rd9126b2a) {
  d: path("m16 12 3 -3");
}

:global(.rt0qgebuc) {
  d: path("m14 9 3 -3");
}

:global(.s_c1vbwpu) {
  d: path("m3 21 8 -8c2 2 3 5 2 8Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
