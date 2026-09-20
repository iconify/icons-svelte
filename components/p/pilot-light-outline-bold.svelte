<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nzpsuduik"/><path class="cma40lsnw"/><path class="rrv-npbwa"/><path class="ruqrtab9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pilot-light-outline-bold" {...props}></Icon>
<style>
:global(.cma40lsnw) {
  d: path("M5.5 16.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nzpsuduik) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.rrv-npbwa) {
  d: path("M7.5 10.5V13");
}

:global(.ruqrtab9h) {
  d: path("m10 14 2 -2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
