<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uwrxavbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dnshero" {...props}></Icon>
<style>
:global(.uwrxavbst) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.3 16.15L4.5 35.85l35.6 3.9l-17.6-7.4L43.5 11L7.3 8.25Z");
}

</style>
