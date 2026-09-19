<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rxzu2vbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:quivr" {...props}></Icon>
<style>
:global(.rxzu2vbez) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.607 32.812a21.498 21.498 0 1 1 .281-16.97M22.909 24l19.383 19.442");
}

</style>
