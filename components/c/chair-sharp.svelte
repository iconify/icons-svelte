<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7nn7wmoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:chair-sharp" {...props}></Icon>
<style>
:global(.l7nn7wmoc) {
  fill: currentColor;
  d: path("M4 21v-2H1v-9h4v5h14v-5h4v9h-3v2h-2v-2H6v2zm3-8V8H4V3h16v5h-3v5z");
}

</style>
