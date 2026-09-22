<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx03zlrcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:markdown-document-sharp" {...props}></Icon>
<style>
:global(.bx03zlrcd) {
  fill: currentColor;
  d: path("M12 22v-9h10v9h-2v-7h-2v5h-2v-5h-2v7zm-9-1V3h18v8H7v2h3v2H7v2h3v4z");
}

</style>
