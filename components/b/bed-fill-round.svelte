<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0sghcbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bed-fill-round" {...props}></Icon>
<style>
:global(.z0sghcbxe) {
  fill: currentColor;
  d: path("M4 8h2v9H4v2a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Zm4 9V8h9a5 5 0 0 1 5 5v6a1 1 0 0 1-2 0v-2Z");
}

</style>
