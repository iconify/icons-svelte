<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vzrj8oblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nextcloudnotes" {...props}></Icon>
<style>
:global(.vzrj8oblu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.272 12.416L39.188 5.5H9.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4V15.834l-3.405 3.406m-6.823-6.824l6.823 6.824l-11.803 11.803l-10.264 3.44l3.44-10.263z");
}

</style>
