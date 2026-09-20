<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vyks9vbfn"/><path class="mpjdm200q"/><path class="tkeq0bpvv"/><path class="x2tju3bnd"/><path class="bfi7-obrv"/><path class="qj5yzibzr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:offline-map-outline-bold" {...props}></Icon>
<style>
:global(.bfi7-obrv) {
  d: path("M9.5 11.5 12 14l2.5 -2.5");
}

:global(.mpjdm200q) {
  d: path("M6 4v16");
}

:global(.qj5yzibzr) {
  d: path("M9 16.5h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tkeq0bpvv) {
  d: path("M18 4v16");
}

:global(.vyks9vbfn) {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.x2tju3bnd) {
  d: path("M12 7v7");
}

</style>
