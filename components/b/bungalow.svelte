<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re4p3_gqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bungalow" {...props}></Icon>
<style>
:global(.re4p3_gqf) {
  fill: currentColor;
  d: path("M8 20v-6.796l-1.196 1.904l-.854-.512L12 4.885l6.03 9.711l-.853.512L16 13.223V20h-3.23v-3.77h-1.54V20zm3.23-6h1.54v-1.538h-1.54z");
}

</style>
