<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ird0rqbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:imagingedgemobile" {...props}></Icon>
<style>
:global(.ird0rqbwu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.25 4.5h6.5V11h6.5v32.5H7.75V11h19.5Zm0 6.5v6.51h-13V37h19.5V11Zm0 0");
}

</style>
