<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d92lyn2ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-selector-tool-outline" {...props}></Icon>
<style>
:global(.d92lyn2ge) {
  fill: currentColor;
  d: path("M8 13.75L9.975 11h4.25L8 6.1zM13.775 22l-3.625-7.8L6 20V2l14 11h-7.1l3.6 7.725zm-3.8-11");
}

</style>
