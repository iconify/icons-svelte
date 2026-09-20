<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhvbqhb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:markdown-sharp" {...props}></Icon>
<style>
:global(.fhvbqhb3b) {
  fill: currentColor;
  d: path("m16 14.692l2.558-2.557l-.608-.633l-1.508 1.489V9.308h-.884v3.683l-1.508-1.489l-.608.633zM3 19V5h18v14zm2.808-4.308h.884v-4.5h1.616v3h.884v-3h1.616v4.5h.884V9.308H5.808z");
}

</style>
