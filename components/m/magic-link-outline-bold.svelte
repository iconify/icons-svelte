<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a0z9iab1m"/><path class="e2nq-yvbg"/><path class="xidycypec"/><path class="drjiz3bcf"/><path class="gnu2dod3i"/><path class="cc9vvy32g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:magic-link-outline-bold" {...props}></Icon>
<style>
:global(.a0z9iab1m) {
  d: path("M14 2h2.5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3h-9a3 3 0 0 1 -3 -3V5a3 3 0 0 1 3 -3H10");
}

:global(.cc9vvy32g) {
  d: path("M10.5 8.5H15");
}

:global(.drjiz3bcf) {
  d: path("M12 21h2.5");
}

:global(.e2nq-yvbg) {
  d: path("M12 15v6");
}

:global(.gnu2dod3i) {
  d: path("M8 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xidycypec) {
  d: path("M12 18h3");
}

</style>
