<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqvutybue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:indeterminate-check-box-sharp" {...props}></Icon>
<style>
:global(.hqvutybue) {
  fill: currentColor;
  d: path("M7.5 12.5h9v-1h-9zM4 20V4h16v16z");
}

</style>
