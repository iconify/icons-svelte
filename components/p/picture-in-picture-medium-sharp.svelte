<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzf58kbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:picture-in-picture-medium-sharp" {...props}></Icon>
<style>
:global(.fzf58kbwi) {
  fill: currentColor;
  d: path("M8 16V8h10v8zm-6 4v-2h18V4h2v16z");
}

</style>
