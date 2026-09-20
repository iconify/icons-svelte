<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="dgh7jhswh"/><path class="qi8hfc1ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:latin-cross" {...props}></Icon>
<style>
:global(.dgh7jhswh) {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

:global(.qi8hfc1ax) {
  fill: var(--svg-color--fff, #fff);
  d: path("M26 10h-6V4a1 1 0 0 0-1-1h-2a1 1 0 0 0-1 1v6h-6a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h6v18a1 1 0 0 0 1 1h2a1 1 0 0 0 1-1V14h6a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1");
}

</style>
