<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6kam2bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:bookmark-search-24-filled" {...props}></Icon>
<style>
:global(.d6kam2bsw) {
  fill: currentColor;
  d: path("M19.107 9.168a4.5 4.5 0 1 1 1.06-1.06l2.613 2.612a.75.75 0 1 1-1.06 1.06zM19.5 5.5a3 3 0 1 0-6 0a3 3 0 0 0 6 0m-.5 4.976v10.769a.75.75 0 0 1-1.188.609l-5.81-4.181l-5.812 4.18a.75.75 0 0 1-1.188-.608V6.249a3.25 3.25 0 0 1 3.25-3.25H11.6a5.5 5.5 0 0 0 7.35 7.426z");
}

</style>
