<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaiaww9ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:chair-alt-sharp" {...props}></Icon>
<style>
:global(.oaiaww9ao) {
  fill: currentColor;
  d: path("M5 21v-9h3v-2H5V3h14v7h-3v2h3v9h-2v-3H7v3zm5-9h4v-2h-4z");
}

</style>
