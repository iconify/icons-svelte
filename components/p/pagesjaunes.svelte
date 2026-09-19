<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b94vjdbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pagesjaunes" {...props}></Icon>
<style>
:global(.b94vjdbfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.162 8.839v4.933M42.5 9.44v11.01c0 6.498-6.257 18.711-17.146 18.711C12.359 39.161 5.5 28.994 5.5 28.994");
}

</style>
