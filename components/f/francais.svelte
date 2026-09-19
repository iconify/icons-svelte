<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mvq8bpyhp"/><path class="me0xezqrh"/><path class="eskcl0gdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:francais" {...props}></Icon>
<style>
:global(.eskcl0gdm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.663 8.276h7v14h-7z");
}

:global(.me0xezqrh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.663 8.276h7v14h-7zm7 0h7v14h-7z");
}

:global(.mvq8bpyhp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.726 4.5H10.4a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h2.326m0-39v39H37.6a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2Z");
}

</style>
