<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moq-wfzvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:memory-alt-sharp" {...props}></Icon>
<style>
:global(.moq-wfzvd) {
  fill: currentColor;
  d: path("M6 15h2V9H6zm5 0h2V9h-2zm5 0h2V9h-2zM5 21v-2H2V5h3V3h2v2h4V3h2v2h4V3h2v2h3v14h-3v2h-2v-2h-4v2h-2v-2H7v2z");
}

</style>
