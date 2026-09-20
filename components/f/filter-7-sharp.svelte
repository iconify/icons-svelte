<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le4vp4bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:filter-7-sharp" {...props}></Icon>
<style>
:global(.le4vp4bvi) {
  fill: currentColor;
  d: path("M11.154 14.5h1.038L16 6.5v-1h-5v1h3.962zM6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>
