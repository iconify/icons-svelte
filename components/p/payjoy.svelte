<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ket8e4bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:payjoy" {...props}></Icon>
<style>
:global(.ket8e4bex) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 34c8.026-13.902 23.657-23.925 37-27.5c-13.326 7.694-24.392 16.626-35 35c35 0 35-6.545 35-35c-30.99 0-37 0-37 27.5");
}

</style>
