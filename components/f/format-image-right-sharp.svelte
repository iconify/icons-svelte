<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5j3c_ees"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-image-right-sharp" {...props}></Icon>
<style>
:global(.o5j3c_ees) {
  fill: currentColor;
  d: path("M11 17V7h10v10zm-8 4v-2h18v2zm0-4v-2h6v2zm0-4v-2h6v2zm0-4V7h6v2zm0-4V3h18v2z");
}

</style>
