<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne6zcz2tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:position-bottom-left-sharp" {...props}></Icon>
<style>
:global(.ne6zcz2tb) {
  fill: currentColor;
  d: path("M6 17h9v-3H6zm-3 4V3h18v18z");
}

</style>
