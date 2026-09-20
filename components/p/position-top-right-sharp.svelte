<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmod78cxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:position-top-right-sharp" {...props}></Icon>
<style>
:global(.nmod78cxe) {
  fill: currentColor;
  d: path("M9 10h9V7H9zM3 21V3h18v18z");
}

</style>
