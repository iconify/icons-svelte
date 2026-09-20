<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6039yb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:label-outline-sharp" {...props}></Icon>
<style>
:global(.q6039yb4g) {
  fill: currentColor;
  d: path("M2 20V4h14l6 8l-6 8zm2-2h11l4.5-6L15 6H4zm7.75-6");
}

</style>
