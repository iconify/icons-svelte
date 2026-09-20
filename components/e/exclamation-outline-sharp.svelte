<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf1k4r5sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:exclamation-outline-sharp" {...props}></Icon>
<style>
:global(.bf1k4r5sc) {
  fill: currentColor;
  d: path("M11 14V5h2v9zm0 5v-2h2v2z");
}

</style>
