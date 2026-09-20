<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s90rsqb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:book-sharp" {...props}></Icon>
<style>
:global(.s90rsqb4w) {
  fill: currentColor;
  d: path("M5 21V3h14v18zm7-10.885l2-1.192l2 1.192V4h-4z");
}

</style>
