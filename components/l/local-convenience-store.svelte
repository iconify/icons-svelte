<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knkx5hbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:local-convenience-store" {...props}></Icon>
<style>
:global(.knkx5hbze) {
  fill: currentColor;
  d: path("M19 7V4H5v3H2v13h8v-4h4v4h8V7zm-8 3H9v1h2v1H8V9h2V8H8V7h3zm5 2h-1v-2h-2V7h1v2h1V7h1z");
}

</style>
