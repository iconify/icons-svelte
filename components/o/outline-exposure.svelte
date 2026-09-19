<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnxqldsug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-exposure" {...props}></Icon>
<style>
:global(.vnxqldsug) {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m-1.41 2L5 17.59V5zM6.41 19L19 6.41V19zM6 7h5v1.5H6zm10 5.5h-1.5v2h-2V16h2v2H16v-2h2v-1.5h-2z");
}

</style>
