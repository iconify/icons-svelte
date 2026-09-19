<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h__kugb8b"/><path class="vit_ohddi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:eatsure" {...props}></Icon>
<style>
:global(.h__kugb8b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 12.488h39v23.028h-39zm19.498 23.025V12.484m-8.151 7.298H24m12.237 0H43.5");
}

:global(.vit_ohddi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.577 28.094c5.737 2.368 11.363 2.4 16.846 0");
}

</style>
