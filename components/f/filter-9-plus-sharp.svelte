<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynnzf0bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:filter-9-plus-sharp" {...props}></Icon>
<style>
:global(.ynnzf0bds) {
  fill: currentColor;
  d: path("M6 18V2h16v16zm-4 4V6h2v14h14v2zm8-8h4V6H9v5h3v1h-2zm2-5h-1V8h1zm4.5 4h2v-2h2V9h-2V7h-2v2h-2v2h2z");
}

</style>
