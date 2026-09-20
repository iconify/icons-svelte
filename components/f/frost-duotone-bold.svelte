<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xa9vorq4l"/><path class="vf6v1_8ra"/><path class="l7-6ovvzu"/><path class="d-_x6ccub"/><path class="bod4n0b3z"/><path class="rbmqb921v"/><path class="nhpfz0btj"/><path class="dgfbh6b4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:frost-duotone-bold" {...props}></Icon>
<style>
:global(.bod4n0b3z) {
  d: path("M2 18h20");
}

:global(.d-_x6ccub) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dgfbh6b4z) {
  d: path("M12 9v9");
}

:global(.l7-6ovvzu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 7.5v7m-3.5 0 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nhpfz0btj) {
  d: path("M17 7.5v7m-3.5 0 7 -7");
}

:global(.rbmqb921v) {
  d: path("M7 7.5v7m-3.5 0 7 -7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vf6v1_8ra) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 7.5v7m-3.5 0 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xa9vorq4l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
