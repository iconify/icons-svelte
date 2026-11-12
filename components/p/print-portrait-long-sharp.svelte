<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebo8zzb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:print-portrait-long-sharp" {...props}></Icon>
<style>
:global(.ebo8zzb9h) {
  fill: currentColor;
  d: path("M5 9.77V7.845h.923V4.681L6.773 4l6.593 2.217v14.26l-.812.546l-6.631-2.294V16.23H5v-1.923h.923V9.769zM14.385 19V5.352L10.475 4H18v15z");
}

</style>
