<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="abnm6smsv"/><path class="u84sg0ngq"/><path class="a2e335b1o"/><path class="h857n5bhq"/><path class="fmjpvzbts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:instruction-outline-bold" {...props}></Icon>
<style>
:global(.a2e335b1o) {
  d: path("M11 10h5");
}

:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.fmjpvzbts) {
  d: path("M11 14h5");
}

:global(.h857n5bhq) {
  d: path("M8 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u84sg0ngq) {
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
