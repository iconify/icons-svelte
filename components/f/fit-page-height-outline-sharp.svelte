<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uer-4wdba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:fit-page-height-outline-sharp" {...props}></Icon>
<style>
:global(.uer-4wdba) {
  fill: currentColor;
  d: path("M9.462 8.808h5.077L12 6.269zM12 17.73l2.539-2.539H9.46zM19 21H5V3h14zm-1-1V4H6v16zm0-16H6z");
}

</style>
