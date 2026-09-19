<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e3ssygbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:oneplus-connect" {...props}></Icon>
<style>
:global(.e3ssygbgp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.247 34.25l35.507-20.5L24 3.5L6.247 13.75zL24 44.5l17.754-10.25l-35.507-20.5");
}

</style>
