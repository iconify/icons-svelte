<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d26mu-byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:mode-comment" {...props}></Icon>
<style>
:global(.d26mu-byc) {
  fill: currentColor;
  d: path("M21.99 4c0-1.1-.89-2-1.99-2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h14l4 4z");
}

</style>
