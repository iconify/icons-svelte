<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="eguxldbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:door-light" {...props}></Icon>
<style>
:global(.eguxldbne) {
  fill: currentColor;
  d: path("M232 218h-26V40a14 14 0 0 0-14-14H64a14 14 0 0 0-14 14v178H24a6 6 0 0 0 0 12h208a6 6 0 0 0 0-12M62 40a2 2 0 0 1 2-2h128a2 2 0 0 1 2 2v178H62Zm104 92a10 10 0 1 1-10-10a10 10 0 0 1 10 10");
}

</style>
