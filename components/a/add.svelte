<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzffklbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:add" {...props}></Icon>
<style>
:global(.vzffklbwm) {
  fill: currentColor;
  d: path("M11 13H5v-2h6V5h2v6h6v2h-6v6h-2z");
}

</style>
