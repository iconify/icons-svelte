<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyubxpfrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:align-space-between-outline-sharp" {...props}></Icon>
<style>
:global(.pyubxpfrq) {
  fill: currentColor;
  d: path("M7.5 6V4H3V3h18v1h-4.5v2zM3 21v-1h4.5v-2h9v2H21v1z");
}

</style>
