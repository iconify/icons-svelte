<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2u-dxewg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-back-ios-outline" {...props}></Icon>
<style>
:global(.z2u-dxewg) {
  fill: currentColor;
  d: path("M10 22L0 12L10 2l1.775 1.775L3.55 12l8.225 8.225z");
}

</style>
