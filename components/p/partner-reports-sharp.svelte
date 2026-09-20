<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf3hn2w_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:partner-reports-sharp" {...props}></Icon>
<style>
:global(.nf3hn2w_r) {
  fill: currentColor;
  d: path("M11.5 12.846V4h1v8.846zM4 20v-4.038h1V19h14v-3.038h1V20zm7.308-3.384V15.23h1.384v1.385z");
}

</style>
