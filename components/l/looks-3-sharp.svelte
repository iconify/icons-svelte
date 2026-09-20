<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4oh-kbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:looks-3-sharp" {...props}></Icon>
<style>
:global(.p4oh-kbtv) {
  fill: currentColor;
  d: path("M9 17h6V7H9v2h4v2h-2v2h2v2H9zm-6 4V3h18v18z");
}

</style>
