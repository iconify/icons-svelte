<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwwb29b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:dataset-sharp" {...props}></Icon>
<style>
:global(.jwwb29b-d) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm3.5-9.5h3v-3h-3zm6 0h3v-3h-3zm-6 6h3v-3h-3zm6 0h3v-3h-3z");
}

</style>
