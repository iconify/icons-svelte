<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8blvqbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:inbox-fill-sharp" {...props}></Icon>
<style>
:global(.v8blvqbap) {
  fill: currentColor;
  d: path("M22 4v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1M7 12c.265 0 .52.105.707.293L10.414 15h3.172l2.707-2.707A1 1 0 0 1 17 12h3V5H4v7Z");
}

</style>
