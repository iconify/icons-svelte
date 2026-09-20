<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgsocwb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:pipeline-24-filled" {...props}></Icon>
<style>
:global(.vgsocwb5g) {
  fill: currentColor;
  d: path("M2 6a2 2 0 1 1 4 0v11a2 2 0 1 1-4 0zm16 0a2 2 0 1 1 4 0v11a2 2 0 1 1-4 0zm-1.5 0h-9v11h9z");
}

</style>
