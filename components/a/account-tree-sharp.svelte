<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4fkknl6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:account-tree-sharp" {...props}></Icon>
<style>
:global(.u4fkknl6y) {
  fill: currentColor;
  d: path("M15 21v-3h-4V8H9v3H2V3h7v3h6V3h7v8h-7V8h-2v8h2v-3h7v8z");
}

</style>
