<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3izwg3ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:drop-shadow-fill-sharp" {...props}></Icon>
<style>
:global(.r3izwg3ac) {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm5 17h13V7a1 1 0 0 1 2 0v14a1 1 0 0 1-1 1H7a1 1 0 0 1 0-2");
}

</style>
