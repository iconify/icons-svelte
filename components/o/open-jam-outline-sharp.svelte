<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk4x_jshq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:open-jam-outline-sharp" {...props}></Icon>
<style>
:global(.sk4x_jshq) {
  fill: currentColor;
  d: path("M6 21h12v-2h-5v-7.2l1.6 1.6L16 12l-4-4l-4 4l1.4 1.4l1.6-1.6V19H6zm-4-5V3h20v13h-7v-2h5V5H4v9h5v2z");
}

</style>
