<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c69remmqt"/><path class="h6hjz9c7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mychronopost" {...props}></Icon>
<style>
:global(.c69remmqt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 3.5l17.754 10.25v20.5L24 44.5L6.246 34.25v-20.5z");
}

:global(.h6hjz9c7m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 41.084V24L6.246 13.75m35.508 0L26.96 22.292");
}

</style>
