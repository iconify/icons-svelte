<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5348ebvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:align-justify-space-between-sharp" {...props}></Icon>
<style>
:global(.e5348ebvt) {
  fill: currentColor;
  d: path("M20 21v-4.5h-2v-9h2V3h1v18zM3 21V3h1v4.5h2v9H4V21z");
}

</style>
