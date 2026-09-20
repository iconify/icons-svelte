<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m10txfbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:float-landscape-2-sharp" {...props}></Icon>
<style>
:global(.m10txfbrs) {
  fill: currentColor;
  d: path("M12.616 14.385h5v-6h-5zM3 19V5h18v14z");
}

</style>
