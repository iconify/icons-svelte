<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csofxjl1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:open-jam-outline-sharp" {...props}></Icon>
<style>
:global(.csofxjl1n) {
  fill: currentColor;
  d: path("M7 19.77h10v-1h-4.5v-8.547l2.1 2.1l.708-.707L12 8.308l-3.308 3.308l.708.707l2.1-2.1v8.546H7zM3 15V4h18v11h-6v-1h5V5H4v9h5v1z");
}

</style>
