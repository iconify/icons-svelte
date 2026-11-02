<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0xftab-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:banknote-fill-sharp" {...props}></Icon>
<style>
:global(.e0xftab-v) {
  fill: currentColor;
  d: path("M2 6a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm7.236 4.832a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335M7 11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm10.01 0H17a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
