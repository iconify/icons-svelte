<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8mbkua-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:capture-outline-sharp" {...props}></Icon>
<style>
:global(.z8mbkua-z) {
  fill: currentColor;
  d: path("M6 16h12V8H6zm-4 4V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
