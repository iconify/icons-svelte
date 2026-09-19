<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="wgywa24ft"/><path class="hantlbcqq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:habitmaker" {...props}></Icon>
<style>
:global(.hantlbcqq) {
  d: path("m13.412 25.03l6.922 7.06L34.907 17.1");
}

:global(.wgywa24ft) {
  d: path("M18.97 3.098a21.5 21.5 0 0 1 22.826 32.966a21.5 21.5 0 0 1-22.62 8.887M3.537 30.596a21.5 21.5 0 0 1-.09-12.905m2.049-4.638a21.5 21.5 0 0 1 8.985-8.33m.212 38.657a21.5 21.5 0 0 1-9.324-8.65");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
