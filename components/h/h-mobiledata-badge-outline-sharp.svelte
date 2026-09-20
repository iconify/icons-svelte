<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_f63pdrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:h-mobiledata-badge-outline-sharp" {...props}></Icon>
<style>
:global(.h_f63pdrk) {
  fill: currentColor;
  d: path("M8 17h2v-4h4v4h2V7h-2v4h-4V7H8zm-5 4V3h18v18zm2-2h14V5H5zM5 5v14z");
}

</style>
