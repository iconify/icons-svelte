<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ww9c_f71i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:fit-page-height-sharp" {...props}></Icon>
<style>
:global(.ww9c_f71i) {
  fill: currentColor;
  d: path("M9.462 8.808h5.077L12 6.269zM12 17.73l2.539-2.539H9.46zM19 21H5V3h14z");
}

</style>
