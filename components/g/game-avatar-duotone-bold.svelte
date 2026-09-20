<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kaeoqxqgu"/><path class="nn07zobkj"/><path class="qkmhvkbue"/><path class="wu-svqt-l"/><path class="hlkk9_bki"/><path class="tb3ak12-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:game-avatar-duotone-bold" {...props}></Icon>
<style>
:global(.hlkk9_bki) {
  d: path("M7 10c0 4 2 6 5 6s5 -2 5 -6");
}

:global(.kaeoqxqgu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 10V5h10v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nn07zobkj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 10c0 4 2 6 5 6s5 -2 5 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qkmhvkbue) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 21v-3h12v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tb3ak12-o) {
  d: path("M6 21v-3h12v3");
}

:global(.wu-svqt-l) {
  d: path("M7 10V5h10v5");
}

</style>
