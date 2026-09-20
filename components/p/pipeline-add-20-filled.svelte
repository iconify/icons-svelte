<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ydc0fkb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:pipeline-add-20-filled" {...props}></Icon>
<style>
:global(.ydc0fkb7t) {
  fill: currentColor;
  d: path("M2 5.5a1.5 1.5 0 0 1 3 0v9a1.5 1.5 0 0 1-3-.001zm12 3.522A5.5 5.5 0 0 0 9.022 14H6V6h8zM15 5.5v3.522a5.5 5.5 0 0 1 3 1.235V5.5a1.5 1.5 0 0 0-3 0m4 9a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V14h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 0 0 0-1H15z");
}

</style>
