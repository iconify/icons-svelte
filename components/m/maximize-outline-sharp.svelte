<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr4c4xbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:maximize-outline-sharp" {...props}></Icon>
<style>
:global(.wr4c4xbqx) {
  fill: currentColor;
  d: path("M4 5V3h16v2z");
}

</style>
