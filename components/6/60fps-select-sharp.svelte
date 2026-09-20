<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgelcxtak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:60fps-select-sharp" {...props}></Icon>
<style>
:global(.kgelcxtak) {
  fill: currentColor;
  d: path("M4 14V4h7v2H6v2h5v6zm2-2h3v-2H6zm7 2V4h7v10zm2-2h3V6h-3zM3 22v-5h2v5zm4 0v-5h2v5zm4 0v-5h2v5zm4 0v-5h6v5z");
}

</style>
