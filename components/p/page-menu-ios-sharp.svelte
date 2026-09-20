<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9h19ku1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:page-menu-ios-sharp" {...props}></Icon>
<style>
:global(.p9h19ku1c) {
  fill: currentColor;
  d: path("M3 21v-2h12v2zm0-4v-2h18v2zm0-4V3h18v10z");
}

</style>
