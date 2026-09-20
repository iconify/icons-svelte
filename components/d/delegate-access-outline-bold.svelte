<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pemn838wn"/><path class="ia4sldbfw"/><path class="ubqf9ccbc"/><path class="kxfa7js9d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:delegate-access-outline-bold" {...props}></Icon>
<style>
:global(.ia4sldbfw) {
  d: path("M3 21a9 9 0 0 1 18 0");
}

:global(.kxfa7js9d) {
  d: path("m13 14.5 2.5 2.5 -2.5 2.5");
}

:global(.pemn838wn) {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ubqf9ccbc) {
  d: path("M9 17h6.5");
}

</style>
