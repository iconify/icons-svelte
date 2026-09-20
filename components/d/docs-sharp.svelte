<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngma_9qff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:docs-sharp" {...props}></Icon>
<style>
:global(.ngma_9qff) {
  fill: currentColor;
  d: path("M12 2v7h7v13H5V2zm2 0l5 5h-5zM9 19h4v-2H9zm0-4h6v-2H9z");
}

</style>
