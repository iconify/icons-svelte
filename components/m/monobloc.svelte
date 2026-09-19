<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vgh0jfbzr"/><path class="cs4w9bzmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:monobloc" {...props}></Icon>
<style>
:global(.cs4w9bzmp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.897 13.998v19.5l17.077 9.75l17.077-9.75v-19.5m-17.077 29.25v-19.5");
}

:global(.vgh0jfbzr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.051 13.998l-17.077-9.75l-17.077 9.75l17.077 9.75z");
}

</style>
