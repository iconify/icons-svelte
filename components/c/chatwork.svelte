<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f8qchv53z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:chatwork" {...props}></Icon>
<style>
:global(.f8qchv53z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.3 12.4a6.9 6.9 0 1 1 6.9 6.9h-6.9zm7.4 23.2a6.9 6.9 0 1 1-6.9-6.9h6.9zm-15.3-7.9a6.9 6.9 0 1 1 6.9-6.9v6.9zm23.2-7.4a6.9 6.9 0 1 1-6.9 6.9v-6.9z");
}

</style>
