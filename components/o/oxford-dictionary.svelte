<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k55af6bev"/><path class="v4ol65b0r"/><path class="l-w6tywkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:oxford-dictionary" {...props}></Icon>
<style>
:global(.k55af6bev) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 6.45v35.1a1.95 1.95 0 0 0 1.95 1.95h2.376v-39H10.35A1.95 1.95 0 0 0 8.4 6.45m4.326-1.95v39H37.65a1.95 1.95 0 0 0 1.95-1.95V6.45a1.95 1.95 0 0 0-1.95-1.95Z");
}

:global(.l-w6tywkp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.663 18l-6.634 4.683L17.663 30");
}

:global(.v4ol65b0r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.663 18h17v12h-17zm8.5 12V18m-8.5 6h17m-17-6l17 12");
}

</style>
