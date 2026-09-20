<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b-pphqpeq"/><path class="sfnyx4wnk"/><path class="p1d_2-vic"/><path class="u9kikz_ju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rootless-container-outline-bold" {...props}></Icon>
<style>
:global(.b-pphqpeq) {
  d: path("M3 8a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.p1d_2-vic) {
  d: path("M11.5 10.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sfnyx4wnk) {
  d: path("M6 6v14");
}

:global(.u9kikz_ju) {
  d: path("M9.5 16.5a4 4 0 0 1 8 0");
}

</style>
