<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkn5vwbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-chevron-left" {...props}></Icon>
<style>
:global(.tkn5vwbtp) {
  fill: currentColor;
  d: path("M15.41 7.41L14 6l-6 6l6 6l1.41-1.41L10.83 12z");
}

</style>
