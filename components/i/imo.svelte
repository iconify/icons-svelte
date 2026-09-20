<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t95zvacjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:imo" {...props}></Icon>
<style>
:global(.t95zvacjd) {
  d: path("M13.588 21h-8.47V10.962L13.588 3zm2.647 0V8.538l2.647 2.768V21z");
}

</style>
