<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egv9hvqtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:density-medium-outline-sharp" {...props}></Icon>
<style>
:global(.egv9hvqtc) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-8v-2h18v2zm0-8V3h18v2z");
}

</style>
