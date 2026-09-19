<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hwtmkvb-t"/><path class="otzcng2or"/><path class="n4ljwhjvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pixelogic" {...props}></Icon>
<style>
:global(.hwtmkvb-t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.14 13.929h8.711v8.711H14.14z");
}

:global(.n4ljwhjvl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.073 37.138l16.82-16.82l5.607 5.607l-16.82 16.82h-5.607z");
}

:global(.otzcng2or) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.56 25.651V7.246a1.984 1.984 0 0 0-1.99-1.991H7.49c-1.104 0-1.99.886-1.99 1.99v30.79c0 1.104.886 1.99 1.99 1.99h4.73a1.99 1.99 0 0 0 1.99-1.99v-6.72h11.686");
}

</style>
