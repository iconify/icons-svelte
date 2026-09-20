<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4e5arffn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-image-break-right-sharp" {...props}></Icon>
<style>
:global(.p4e5arffn) {
  fill: currentColor;
  d: path("M3 5V3h18v2zm8 12V7h10v10zm-8 4v-2h18v2z");
}

</style>
