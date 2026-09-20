<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldhrq4agx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bedroom-child-sharp" {...props}></Icon>
<style>
:global(.ldhrq4agx) {
  fill: currentColor;
  d: path("M6.616 16.385H7.5v-1.5h9v1.5h.885V11.15h-1.5V8.23h-7.77v2.92h-1.5zM9 11.115v-2h6v2zM7.5 14v-2h9v2zM3 21V3h18v18z");
}

</style>
