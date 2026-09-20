<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ivc0p9bus"/><path class="d1zyr9bfc"/><path class="rnnki-bvy"/><path class="ikiprn9sq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:luggage-scale-outline-bold" {...props}></Icon>
<style>
:global(.d1zyr9bfc) {
  d: path("M12 4v4");
}

:global(.ikiprn9sq) {
  d: path("M9 14h6");
}

:global(.ivc0p9bus) {
  d: path("M6 4h12");
}

:global(.rnnki-bvy) {
  d: path("M6 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
