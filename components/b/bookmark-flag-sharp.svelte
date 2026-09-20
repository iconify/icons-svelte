<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4my6-t8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:bookmark-flag-sharp" {...props}></Icon>
<style>
:global(.a4my6-t8y) {
  fill: currentColor;
  d: path("M9.5 14H11v-3h4.5L14 9l1.5-2h-6zM5 21V3h14v18l-7-3z");
}

</style>
