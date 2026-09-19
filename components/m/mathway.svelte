<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="okkfocb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mathway" {...props}></Icon>
<style>
:global(.okkfocb3s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5v37h5.975L24 24L11.475 5.5Zm31.025 0L24 24l12.525 18.5H42.5v-37Z");
}

</style>
