<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xpfd0t17h"/><path class="fxxri_u_v"/><path class="b_15o8exz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:emoji-newspaper" {...props}></Icon>
<style>
:global(.b_15o8exz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.867 19.718h13.455v13.455H8.867z");
}

:global(.fxxri_u_v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.505 12.244h33.628v26.903H5.505z");
}

:global(.xpfd0t17h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.133 39.147h1.61c1.115 0 1.752-.677 1.752-1.791V8.853H8.868m-.001 7.425H35.77m-9.706 4.112h9.706m-9.706 4.283h9.706m-9.706 4.282h9.706m-9.706 4.282h9.706");
}

</style>
