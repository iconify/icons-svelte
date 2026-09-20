<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l5k4yiboy"/><path class="x6ma3nbxt"/><path class="h2-2dgnfu"/><path class="ae-e09b3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:compass-rose-duotone-thin" {...props}></Icon>
<style>
:global(.ae-e09b3w) {
  d: path("M3 12h18");
}

:global(.h2-2dgnfu) {
  d: path("M12 3v18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l5k4yiboy) {
  fill: currentColor;
  d: path("m12 3 9 9 -9 9 -9 -9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x6ma3nbxt) {
  d: path("m12 3 9 9 -9 9 -9 -9Z");
}

</style>
