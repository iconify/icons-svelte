<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np36fhowe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:background-grid-small-sharp" {...props}></Icon>
<style>
:global(.np36fhowe) {
  fill: currentColor;
  d: path("M3 21h3v-3H3zm5 0h3v-3H8zm5 0h3v-3h-3zm5 0h3v-3h-3zM3 6h3V3H3zm0 5h3V8H3zm0 5h3v-3H3zM8 6h3V3H8zm0 5h3V8H8zm0 5h3v-3H8zm5-10h3V3h-3zm0 5h3V8h-3zm0 5h3v-3h-3zm5-10h3V3h-3zm0 5h3V8h-3zm0 5h3v-3h-3z");
}

</style>
