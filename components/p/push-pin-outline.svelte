<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3q6y6n-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:push-pin-outline" {...props}></Icon>
<style>
:global(.a3q6y6n-u) {
  fill: currentColor;
  d: path("M15 12.423L16.577 14v1H12.5v5l-.5.5l-.5-.5v-5H7.423v-1L9 12.423V5H8V4h8v1h-1zM8.85 14h6.3L14 12.85V5h-4v7.85zM12 14");
}

</style>
