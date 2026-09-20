<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9u9z1bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bedroom-parent-sharp" {...props}></Icon>
<style>
:global(.i9u9z1bic) {
  fill: currentColor;
  d: path("M5.616 16.462H6.5v-1.577h11v1.577h.885v-5.385h-.75V8.231H6.365v2.846h-.75zm6.826-5.385V9.116h4.308v1.961zm-5.192 0V9.116h4.308v1.961zM6.5 14v-2h11v2zM3 21V3h18v18z");
}

</style>
