<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnyzqsw2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-short-text" {...props}></Icon>
<style>
:global(.gnyzqsw2h) {
  fill: currentColor;
  d: path("M4 9h16v2H4zm0 4h10v2H4z");
}

</style>
