<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tqys-8bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:finn-mobile" {...props}></Icon>
<style>
:global(.tqys-8bnk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 39.315V19.51L24 29.673L42.5 19.51v19.805m-37-30.63L24 18.848L42.5 8.685");
}

</style>
