<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="riojvwb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:currency-jpy-thin" {...props}></Icon>
<style>
:global(.riojvwb8q) {
  fill: currentColor;
  d: path("M203.1 50.53L136.44 132H176a4 4 0 0 1 0 8h-44v24h44a4 4 0 0 1 0 8h-44v44a4 4 0 0 1-8 0v-44H80a4 4 0 0 1 0-8h44v-24H80a4 4 0 0 1 0-8h39.56L52.9 50.53a4 4 0 0 1 6.2-5.06l68.9 84.21l68.9-84.21a4 4 0 1 1 6.2 5.06");
}

</style>
