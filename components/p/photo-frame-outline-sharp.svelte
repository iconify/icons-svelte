<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwhui3bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:photo-frame-outline-sharp" {...props}></Icon>
<style>
:global(.jwhui3bcp) {
  fill: currentColor;
  d: path("M5 21v-2H1V4h22v15h-4v2zm-2-4h18V6H3zm2-2h14l-4.5-6l-3.5 4.5l-2.5-3zm-2 2V6z");
}

</style>
