<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lb-4kebew"/><path class="wpewy1b0c"/><path class="ext7qtobs"/><path class="ia95t8sod"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:escalation-duotone-thin" {...props}></Icon>
<style>
:global(.ext7qtobs) {
  d: path("M3 19h5v-5h5V9h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ia95t8sod) {
  d: path("m16 6 3 3 -3 3");
}

:global(.lb-4kebew) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h5v-5h5V9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wpewy1b0c) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 6 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
