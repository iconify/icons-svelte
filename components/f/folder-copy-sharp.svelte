<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8b8sj4as"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:folder-copy-sharp" {...props}></Icon>
<style>
:global(.z8b8sj4as) {
  fill: currentColor;
  d: path("M1 21V6h2v13h17v2zm4-4V2h7l2 2h9v13z");
}

</style>
