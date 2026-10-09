<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9n0g34le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:looks-0-outline-sharp" {...props}></Icon>
<style>
:global(.h9n0g34le) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V5H5zm0 0V5zm4.5-2.5h5v-9h-5zm1-1v-7h3v7z");
}

</style>
