<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eu09dnbci"/><path class="hmekf-bdm"/><path class="nm1tlbreh"/><path class="v5srdkbdr"/><path class="i12kcgemc"/><path class="axz8bmb1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cache-build-duotone-thin" {...props}></Icon>
<style>
:global(.axz8bmb1c) {
  d: path("M17 4v6");
}

:global(.eu09dnbci) {
  fill: currentColor;
  d: path("M3 15a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hmekf-bdm) {
  d: path("M3 15a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i12kcgemc) {
  d: path("m10 6.5 2 2 2 -2");
}

:global(.nm1tlbreh) {
  d: path("M7 4v6");
}

:global(.v5srdkbdr) {
  d: path("M12 2v3.5");
}

</style>
