<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t420hac0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:roofing-outline" {...props}></Icon>
<style>
:global(.t420hac0k) {
  fill: currentColor;
  d: path("M9.385 19v-5.23h5.23V19zm1-1h3.23v-3.23h-3.23zm-7.781-5.77L2 11.44L12 4l4.346 3.223V5h1.885v3.62l3.788 2.819l-.603.792L12 5.256zM12 16.385");
}

</style>
