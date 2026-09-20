<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fsxvwybci"/><path class="z_2regihn"/><path class="foqrfsbtg"/><path class="v5td4_4qf"/><path class="km504hb-m"/><path class="w7wsu271f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:circuit-break-duotone-bold" {...props}></Icon>
<style>
:global(.foqrfsbtg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8.5 16 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fsxvwybci) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 16h6.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.km504hb-m) {
  d: path("M15.5 16H22");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v5td4_4qf) {
  d: path("M2 16h6.5");
}

:global(.w7wsu271f) {
  d: path("m8.5 16 8 -8");
}

:global(.z_2regihn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15.5 16H22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
