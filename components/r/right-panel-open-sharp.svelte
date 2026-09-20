<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbor5-b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:right-panel-open-sharp" {...props}></Icon>
<style>
:global(.bbor5-b8f) {
  fill: currentColor;
  d: path("M11.5 16V8l-4 4zM5 19h9V5H5zm-2 2V3h18v18z");
}

</style>
