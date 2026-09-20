<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hszmfabuj"/><path class="k-u6mjjod"/><path class="d568e3b_k"/><path class="hm5wf8bkx"/><path class="t407ddc6o"/><path class="hmleclbdj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:decoder-duotone-bold" {...props}></Icon>
<style>
:global(.d568e3b_k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hm5wf8bkx) {
  d: path("m20 3 -6 6v6l6 6");
}

:global(.hmleclbdj) {
  d: path("m8 9 3 3 -3 3");
}

:global(.hszmfabuj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m20 3 -6 6v6l6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k-u6mjjod) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t407ddc6o) {
  d: path("M3 12h8");
}

</style>
