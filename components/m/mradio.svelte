<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vtgli5gtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mradio" {...props}></Icon>
<style>
:global(.vtgli5gtu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.8 25.888c4.446-1.169 7.73-5.204 7.73-10.018c0-5.727-4.643-10.37-10.37-10.37H9.038v37h29.925zm7.673-11.136H9.037m23.533 9.252H9.037m24.265 9.244H9.037");
}

</style>
