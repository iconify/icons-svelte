<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mocjavemi"/><path class="bok4f3ael"/><path class="zwzskpvdk"/><path class="t6ludmxih"/><path class="nd_l8-t2z"/><path class="zhmw1tbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-listen-duotone-thin" {...props}></Icon>
<style>
:global(.bok4f3ael) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4.76 16.24a6 6 0 0 1 0 -8.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mocjavemi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6.88 14.12a3 3 0 0 1 0 -4.24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nd_l8-t2z) {
  d: path("M4.76 16.24a6 6 0 0 1 0 -8.5");
}

:global(.t6ludmxih) {
  d: path("M6.88 14.12a3 3 0 0 1 0 -4.24");
}

:global(.zhmw1tbis) {
  d: path("M18.69 8.37a4 4 0 1 1 -3.38 0");
}

:global(.zwzskpvdk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.69 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
