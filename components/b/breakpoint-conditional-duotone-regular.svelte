<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n5662cbho"/><path class="tenhr0_oh"/><path class="tee3b-ble"/><path class="jlpxneb5g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:breakpoint-conditional-duotone-regular" {...props}></Icon>
<style>
:global(.jlpxneb5g) {
  d: path("M9 8v8");
}

:global(.n5662cbho) {
  fill: currentColor;
  d: path("m6 9 3 3 -3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tee3b-ble) {
  d: path("M10 12h11");
}

:global(.tenhr0_oh) {
  d: path("m6 9 3 3 -3 3 -3 -3Z");
}

</style>
