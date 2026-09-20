<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4ccgnqpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:bed-sharp" {...props}></Icon>
<style>
:global(.o4ccgnqpv) {
  fill: currentColor;
  d: path("M2 19v-9h1V5h18v5h1v9h-2v-2H4v2zm11-9h6V7h-6zm-8 0h6V7H5z");
}

</style>
