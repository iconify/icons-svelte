<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mthupbbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:keyboard-double-arrow-down-sharp" {...props}></Icon>
<style>
:global(.mthupbbfs) {
  fill: currentColor;
  d: path("m12 19l-6-6l1.4-1.4l4.6 4.575l4.6-4.575L18 13zm0-6L6 7l1.4-1.4l4.6 4.575L16.6 5.6L18 7z");
}

</style>
