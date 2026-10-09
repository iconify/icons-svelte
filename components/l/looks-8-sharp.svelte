<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sg9os3qwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:looks-8-sharp" {...props}></Icon>
<style>
:global(.sg9os3qwc) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V5H5zm0 0V5h14v14zm4-2h6v-4l-1-1l1-1V7H9v4l1 1l-1 1zm2-6V9h2v2zm0 4v-2h2v2z");
}

</style>
