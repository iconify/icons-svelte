<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6swe7bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:float-portrait-2-sharp" {...props}></Icon>
<style>
:global(.m6swe7bil) {
  fill: currentColor;
  d: path("M8.385 11.385h6v-5h-6zM19 21H5V3h14z");
}

</style>
