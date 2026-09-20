<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y1lw-i3ot"/><path class="ah8uvpf1o"/><path class="svo3n0y2p"/><path class="opzncliew"/><path class="fbw2ldgtv"/><path class="x6walc0pr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hedge-trimmer-duotone-thin" {...props}></Icon>
<style>
:global(.ah8uvpf1o) {
  d: path("M3 10h13");
}

:global(.fbw2ldgtv) {
  d: path("M12 10v7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.opzncliew) {
  d: path("M8 10v7");
}

:global(.svo3n0y2p) {
  d: path("M4 10v7");
}

:global(.x6walc0pr) {
  d: path("M16 7h5v6h-5Z");
}

:global(.y1lw-i3ot) {
  fill: currentColor;
  d: path("M16 7h5v6h-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
