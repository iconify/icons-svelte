<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3b_t_-_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:page-margins-fill-sharp" {...props}></Icon>
<style>
:global(.n3b_t_-_x) {
  fill: currentColor;
  d: path("M4 3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Zm6 5v8h4V8Z");
}

</style>
