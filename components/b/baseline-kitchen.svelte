<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxf-a4lkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-kitchen" {...props}></Icon>
<style>
:global(.qxf-a4lkm) {
  fill: currentColor;
  d: path("M20 9V4c0-1.1-.9-2-2-2H6c-1.1 0-2 .9-2 2v5zM8 5h2v3H8zm-4 6v9c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2v-9zm6 6H8v-5h2z");
}

</style>
