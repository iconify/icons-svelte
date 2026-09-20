<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6j6zhbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:align-stretch" {...props}></Icon>
<style>
:global(.p6j6zhbeq) {
  fill: currentColor;
  d: path("M7.5 9.5V4H3V3h18v1h-4.5v5.5zM3 21v-1h4.5v-5.5h9V20H21v1z");
}

</style>
