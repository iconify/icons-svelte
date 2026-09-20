<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4hzxacjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:123-sharp" {...props}></Icon>
<style>
:global(.u4hzxacjw) {
  fill: currentColor;
  d: path("M5.5 15v-4.5H4V9h3v6zM9 15v-3.5h3v-1H9V9h4.5v3.5h-3v1h3V15zm6 0v-1.5h3v-1h-2v-1h2v-1h-3V9h4.5v6z");
}

</style>
