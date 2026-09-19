<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rrupgx0bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:izipay" {...props}></Icon>
<style>
:global(.rrupgx0bw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.626 5.5h30.306l2.442 8.504L28.885 25.04l-4.523-7.418l3.98-3.618H9.978zm32.748 37H10.068l-2.442-8.504L19.115 22.96l4.523 7.418l-3.98 3.618h18.364z");
}

</style>
