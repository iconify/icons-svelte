<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrjrc8b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:crop-21-9-sharp" {...props}></Icon>
<style>
:global(.vrjrc8b7q) {
  fill: currentColor;
  d: path("M2 17V7h20v10z");
}

</style>
