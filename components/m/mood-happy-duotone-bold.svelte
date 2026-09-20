<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o48nut9qz"/><path class="omcxz1ygw"/><path class="asywpnb9d"/><path class="uk0rveqaj"/><path class="rdx5t34om"/><path class="mh3_-obpm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mood-happy-duotone-bold" {...props}></Icon>
<style>
:global(.asywpnb9d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 12a8 8 0 0 1 -16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mh3_-obpm) {
  d: path("M20 12a8 8 0 0 1 -16 0");
}

:global(.o48nut9qz) {
  fill: currentColor;
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.omcxz1ygw) {
  fill: currentColor;
  d: path("M16 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rdx5t34om) {
  d: path("M16 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uk0rveqaj) {
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
