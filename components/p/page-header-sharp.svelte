<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqteh8y2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:page-header-sharp" {...props}></Icon>
<style>
:global(.iqteh8y2k) {
  fill: currentColor;
  d: path("M4 5V4h16v1zm0 15V7.385h16V20z");
}

</style>
