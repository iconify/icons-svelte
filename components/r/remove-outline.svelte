<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9wvvrbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:remove-outline" {...props}></Icon>
<style>
:global(.t9wvvrbjh) {
  fill: currentColor;
  d: path("M5 13v-2h14v2z");
}

</style>
