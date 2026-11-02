<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddcg6pbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:banknote-fill" {...props}></Icon>
<style>
:global(.ddcg6pbyo) {
  fill: currentColor;
  d: path("M5 5h14a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3m4.236 5.832a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335M7 11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm10.01 0H17a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
