<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1meh0tsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:question-answer" {...props}></Icon>
<style>
:global(.l1meh0tsc) {
  fill: currentColor;
  d: path("M21 6h-2v9H6v2c0 .55.45 1 1 1h11l4 4V7c0-.55-.45-1-1-1m-4 6V3c0-.55-.45-1-1-1H3c-.55 0-1 .45-1 1v14l4-4h10c.55 0 1-.45 1-1");
}

</style>
