<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur1q23b4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-selector-tool-sharp" {...props}></Icon>
<style>
:global(.ur1q23b4v) {
  fill: currentColor;
  d: path("m13.775 22l-3.625-7.8L6 20V2l14 11h-7.1l3.6 7.725z");
}

</style>
