<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqywxybaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:line-start-arrow-sharp" {...props}></Icon>
<style>
:global(.vqywxybaf) {
  fill: currentColor;
  d: path("M13 19L2 12l11-7v6h9v2h-9z");
}

</style>
