<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odxncdmnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-flow-diagonal-up-right-24-regular" {...props}></Icon>
<style>
:global(.odxncdmnu) {
  fill: currentColor;
  d: path("M19.78 5.28a.75.75 0 0 0-1.06-1.06l-9.472 9.47a4 4 0 1 0 1.06 1.06zM4.5 17a2.5 2.5 0 1 1 5 0a2.5 2.5 0 0 1-5 0");
}

</style>
