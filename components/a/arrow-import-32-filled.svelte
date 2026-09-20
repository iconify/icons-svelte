<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ig4dgto6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-import-32-filled" {...props}></Icon>
<style>
:global(.ig4dgto6i) {
  fill: currentColor;
  d: path("M28.75 4.5c.69 0 1.25.56 1.25 1.25v20a1.25 1.25 0 1 1-2.5 0v-20c0-.69.56-1.25 1.25-1.25M15.366 7.366a1.25 1.25 0 0 1 1.768 0l7.5 7.5a1.25 1.25 0 0 1 0 1.768l-7.5 7.5a1.25 1.25 0 0 1-1.768-1.768L20.732 17H3.25a1.25 1.25 0 1 1 0-2.5h17.482l-5.366-5.366a1.25 1.25 0 0 1 0-1.768");
}

</style>
