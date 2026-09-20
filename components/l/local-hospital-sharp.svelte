<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5to_7bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:local-hospital-sharp" {...props}></Icon>
<style>
:global(.n5to_7bpx) {
  fill: currentColor;
  d: path("M11.25 16.5h1.5v-3.75h3.75v-1.5h-3.75V7.5h-1.5v3.75H7.5v1.5h3.75zM4 20V4h16v16z");
}

</style>
