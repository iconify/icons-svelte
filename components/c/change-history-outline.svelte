<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwt1zxbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:change-history-outline" {...props}></Icon>
<style>
:global(.wwt1zxbjc) {
  fill: currentColor;
  d: path("M2 20L12 4l10 16zm3.6-2h12.8L12 7.75zm6.4-5.125");
}

</style>
