<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7sih0b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:article-outline-sharp" {...props}></Icon>
<style>
:global(.b7sih0b-b) {
  fill: currentColor;
  d: path("M7.5 16.5h6v-1h-6zm0-4h9v-1h-9zm0-4h9v-1h-9zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
