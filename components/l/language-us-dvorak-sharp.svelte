<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enuxo7m3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:language-us-dvorak-sharp" {...props}></Icon>
<style>
:global(.enuxo7m3r) {
  fill: currentColor;
  d: path("M6 15h3.25V9H6zm-2 2V7h6.25l1 1v8l-1 1zm11.625 0L12.25 7h2l2.375 6.95L19 7h2l-3.375 10z");
}

</style>
