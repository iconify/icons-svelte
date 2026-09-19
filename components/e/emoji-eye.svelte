<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGRTvA9WgL" class="w6vej-bel"/></defs><path class="y3-3bqb8o"/><use href="#SVGRTvA9WgL" class="c-zrgpb5l"/><use href="#SVGRTvA9WgL" class="c-zrgpb5l"/><path class="n7r3v-30a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:emoji-eye" {...props}></Icon>
<style>
:global(.c-zrgpb5l) {
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.n7r3v-30a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.904 23.751c0 4.528 3.684 8.198 8.229 8.198s8.23-3.67 8.23-8.198s-3.683-8.199-8.228-8.2s-8.23 3.669-8.231 8.197z");
}

:global(.w6vej-bel) {
  fill: none;
  stroke: currentColor;
  d: path("M19.647 23.751c-.002 2.469 2.006 4.47 4.484 4.472c2.478.001 4.487-2 4.488-4.467v-.005c.002-2.468-2.006-4.47-4.484-4.471s-4.487 1.998-4.488 4.467z");
}

:global(.y3-3bqb8o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24c0 5.973 8.283 10.816 18.5 10.816S42.5 29.973 42.5 24S34.217 13.184 24 13.184S5.5 18.027 5.5 24");
}

</style>
