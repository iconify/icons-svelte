<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kttw9obaq"/><path class="l1ji318fm"/><path class="zrhbfua-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:grasshopper" {...props}></Icon>
<style>
:global(.kttw9obaq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 19.159c0 7.002 8.458 11.854 17.47 11.854h13.206c0-15.286-16.326-14.974-21.005-19.653c0 0-.52 4.783 2.287 7.799Zm30.676 11.854v5.962m-5.858-5.962v5.962m-4.675-5.962l-5.877 5.878");
}

:global(.l1ji318fm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.488 18.188h5.798a3.214 3.214 0 0 1 3.214 3.215v8.501s-9.012-2.704-9.012-11.716");
}

:global(.zrhbfua-u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.063 11.025c-2.08 2.184-2.575 4.044-2.575 7.163");
}

</style>
