<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmzf6gb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:plug-connect-sharp" {...props}></Icon>
<style>
:global(.nmzf6gb-b) {
  fill: currentColor;
  d: path("M7 20v-1H3v-6H1v-2h2V5h4V4h2v16zm8 0v-4h-4v-2h4v-4h-4V8h4V4h2v1h4v6h2v2h-2v6h-4v1z");
}

</style>
