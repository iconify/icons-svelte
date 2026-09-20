<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnnbb8hlj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:home" {...props}></Icon>
<style>
:global(.wnnbb8hlj) {
  fill: currentColor;
  d: path("M4 21V9l8-6l8 6v12h-6v-7h-4v7z");
}

</style>
