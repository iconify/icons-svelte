<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srqqheb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:content-copy-sharp" {...props}></Icon>
<style>
:global(.srqqheb8i) {
  fill: currentColor;
  d: path("M7.5 17V3h11v14zm-3 3V6.616h1V19h9.385v1z");
}

</style>
