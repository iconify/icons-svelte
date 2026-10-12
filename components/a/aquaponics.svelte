<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j097ke_6j"/><rect class="jkggtjskl"/><path class="wevoy64pr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:aquaponics" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j097ke_6j) {
  d: path("M12 11.5v-5M12 9q-1.14-4.28-5.5-3.5Q7.64 9.78 12 9m0-1.5q4.65.07 5.5-4.5q-4.65-.07-5.5 4.5");
}

:global(.jkggtjskl) {
  width: 18.5px;
  height: 9.75px;
  x: 2.75px;
  y: 11.5px;
  rx: 1.5px;
}

:global(.wevoy64pr) {
  d: path("M7 16.5c1.75-2 4.75-2 6.5 0c-1.75 2-4.75 2-6.5 0m6.5 0l2.5-1.75v3.5Z");
}

</style>
