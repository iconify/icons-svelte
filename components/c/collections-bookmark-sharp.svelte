<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln5_fkbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:collections-bookmark-sharp" {...props}></Icon>
<style>
:global(.ln5_fkbyx) {
  fill: currentColor;
  d: path("M6 18V2h16v16zm-4 4V6h2v14h14v2zM13 4v7l2.5-1.5L18 11V4z");
}

</style>
