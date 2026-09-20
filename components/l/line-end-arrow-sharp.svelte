<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7sn1cb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:line-end-arrow-sharp" {...props}></Icon>
<style>
:global(.t7sn1cb0u) {
  fill: currentColor;
  d: path("M11 19v-6H2v-2h9V5l11 7z");
}

</style>
