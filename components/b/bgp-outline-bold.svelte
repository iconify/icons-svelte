<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="enrpg0aoq"/><path class="gvmyg7bww"/><path class="fadcahsis"/><path class="yhbbndf5c"/><path class="y9-dv_b3q"/><path class="jyj967m8y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bgp-outline-bold" {...props}></Icon>
<style>
:global(.enrpg0aoq) {
  d: path("M9 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.fadcahsis) {
  d: path("M18 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gvmyg7bww) {
  d: path("M2 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.jyj967m8y) {
  d: path("m18 7 -3 3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.y9-dv_b3q) {
  d: path("m6 7 3 3");
}

:global(.yhbbndf5c) {
  d: path("M2 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
