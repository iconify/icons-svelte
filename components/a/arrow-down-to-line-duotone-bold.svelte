<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w1h-xcbkl"/><path class="h1jtp-bio"/><path class="q4otffbry"/><path class="qdn88l2uv"/><path class="g4h6r4ykz"/><path class="pkaragbav"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-down-to-line-duotone-bold" {...props}></Icon>
<style>
:global(.g4h6r4ykz) {
  d: path("M12 4v12");
}

:global(.h1jtp-bio) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pkaragbav) {
  d: path("m8 12 4 4 4 -4");
}

:global(.q4otffbry) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 12 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qdn88l2uv) {
  d: path("M7 20h10");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w1h-xcbkl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 20h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
