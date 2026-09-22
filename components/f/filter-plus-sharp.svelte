<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi8n2yidj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:filter-plus-sharp" {...props}></Icon>
<style>
:global(.vi8n2yidj) {
  fill: currentColor;
  d: path("M8 20v-7L.95 4h18.1L12 13v7zm9 0v-3h-3v-2h3v-3h2v3h3v2h-3v3z");
}

</style>
