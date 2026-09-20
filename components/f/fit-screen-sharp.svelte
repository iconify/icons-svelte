<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdonw_bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:fit-screen-sharp" {...props}></Icon>
<style>
:global(.tdonw_bjr) {
  fill: currentColor;
  d: path("M20 9V6h-3V5h4v4zM3 9V5h4v1H4v3zm14 10v-1h3v-3h1v4zM3 19v-4h1v3h3v1zm3.846-3.846V8.846h10.308v6.308z");
}

</style>
