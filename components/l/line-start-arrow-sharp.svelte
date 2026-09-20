<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kel900s3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:line-start-arrow-sharp" {...props}></Icon>
<style>
:global(.kel900s3c) {
  fill: currentColor;
  d: path("M11.808 16.827L4.212 12l7.596-4.827V11.5h9.115v1h-9.115z");
}

</style>
