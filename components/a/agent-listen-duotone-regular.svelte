<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oxifwccte"/><path class="kh_a7-qjc"/><path class="jql8b-n9t"/><path class="t6ludmxih"/><path class="nd_l8-t2z"/><path class="zhmw1tbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-listen-duotone-regular" {...props}></Icon>
<style>
:global(.jql8b-n9t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.69 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kh_a7-qjc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4.76 16.24a6 6 0 0 1 0 -8.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nd_l8-t2z) {
  d: path("M4.76 16.24a6 6 0 0 1 0 -8.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oxifwccte) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6.88 14.12a3 3 0 0 1 0 -4.24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t6ludmxih) {
  d: path("M6.88 14.12a3 3 0 0 1 0 -4.24");
}

:global(.zhmw1tbis) {
  d: path("M18.69 8.37a4 4 0 1 1 -3.38 0");
}

</style>
