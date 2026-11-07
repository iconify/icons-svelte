<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyaxh5yvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:looks-0-sharp" {...props}></Icon>
<style>
:global(.kyaxh5yvi) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm5.5-3.5h5v-9h-5zm1-1v-7h3v7z");
}

</style>
