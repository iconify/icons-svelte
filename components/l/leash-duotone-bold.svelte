<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yyvm7xbin"/><path class="ca4aen3yr"/><path class="lo7kp72nh"/><path class="n2em18brm"/><path class="fah6drbfn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:leash-duotone-bold" {...props}></Icon>
<style>
:global(.ca4aen3yr) {
  fill: currentColor;
  d: path("M16 18h3v3h-3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fah6drbfn) {
  d: path("M16 18h3v3h-3Z");
}

:global(.lo7kp72nh) {
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.n2em18brm) {
  d: path("M9 10c4 2 6 5 7 8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yyvm7xbin) {
  fill: currentColor;
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
