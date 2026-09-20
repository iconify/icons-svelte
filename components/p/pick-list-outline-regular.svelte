<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j534ltbcb"/><path class="m1mjigbsi"/><path class="d1zyr9bfc"/><path class="teamv5bhf"/><path class="v_xc_lbja"/><path class="aq_yi4bjn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pick-list-outline-regular" {...props}></Icon>
<style>
:global(.aq_yi4bjn) {
  d: path("M11 17h5");
}

:global(.d1zyr9bfc) {
  d: path("M12 4v4");
}

:global(.j534ltbcb) {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.m1mjigbsi) {
  d: path("M4 8h16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.teamv5bhf) {
  d: path("M8 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.v_xc_lbja) {
  d: path("M11 13h5");
}

</style>
