<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubjs4kbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-local-convenience-store" {...props}></Icon>
<style>
:global(.ubjs4kbrj) {
  fill: currentColor;
  d: path("M19 7V4H5v3H2v13h8v-4h4v4h8V7zm1 11h-4v-4H8v4H4V9h3V6h10v3h3zM8 8h2v1H8v3h3v-1H9v-1h2V7H8zm7 1h-1V7h-1v3h2v2h1V7h-1z");
}

</style>
