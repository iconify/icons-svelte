<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jp0xl_big"/><path class="gdqbly48t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:myxl" {...props}></Icon>
<style>
:global(.gdqbly48t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.645 31.085v-3.094h7.021l4.082-6.645H28.645V10.243L22 14.324v9.027");
}

:global(.jp0xl_big) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.551 34.467l-14.598-16.99H8.122l7.298 8.495l-7.298 8.495h8.831l2.883-3.355l2.883 3.355z");
}

</style>
