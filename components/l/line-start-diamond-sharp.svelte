<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p454zibvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:line-start-diamond-sharp" {...props}></Icon>
<style>
:global(.p454zibvy) {
  fill: currentColor;
  d: path("m9 19l-7-7l7-7l6 6h7v2h-7z");
}

</style>
