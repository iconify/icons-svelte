<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_0dfi6tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:add-2" {...props}></Icon>
<style>
:global(.p_0dfi6tt) {
  fill: currentColor;
  d: path("M11.5 20v-7.5H4v-1h7.5V4h1v7.5H20v1h-7.5V20z");
}

</style>
