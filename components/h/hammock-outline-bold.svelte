<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r3uz_wvor"/><path class="vvv_0v-7b"/><path class="auc4o2swl"/><path class="bu35rpbki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hammock-outline-bold" {...props}></Icon>
<style>
:global(.auc4o2swl) {
  d: path("M4 8c0 8 16 8 16 0");
}

:global(.bu35rpbki) {
  d: path("M4 12c0 7 16 7 16 0");
}

:global(.r3uz_wvor) {
  d: path("M4 6v15");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vvv_0v-7b) {
  d: path("M20 6v15");
}

</style>
