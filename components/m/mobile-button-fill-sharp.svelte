<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgx6647tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mobile-button-fill-sharp" {...props}></Icon>
<style>
:global(.rgx6647tg) {
  fill: currentColor;
  d: path("M6 21V3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1m6.01-4H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
