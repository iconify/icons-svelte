<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="acyg6nb1v"/><path class="y99pnbb6w"/><path class="b6mgpfapj"/><path class="lx87koegb"/><path class="gz7owxbeh"/><path class="mow6v4bfc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:network-outline-bold" {...props}></Icon>
<style>
:global(.acyg6nb1v) {
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.b6mgpfapj) {
  d: path("M17 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gz7owxbeh) {
  d: path("m14 10 3 3");
}

:global(.lx87koegb) {
  d: path("m10 10 -3 3");
}

:global(.mow6v4bfc) {
  d: path("M7.5 15h9");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.y99pnbb6w) {
  d: path("M3 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
