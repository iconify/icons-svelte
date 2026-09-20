<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-_thym8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mountain-flag-outline-sharp" {...props}></Icon>
<style>
:global(.k-_thym8w) {
  fill: currentColor;
  d: path("m8.7 12.925l1.375.925L12 12.875l1.925.975l1.325-.875l-1-1.975h-4.6zM5.225 20H18.75l-2.6-5.225l-2.075 1.375L12 15.125L9.925 16.15L7.8 14.75zM2 22L8.4 9H11V2h7l-1 2l1 2h-5v3h2.5L22 22z");
}

</style>
